# たった1日で基本が身に付く! Git超入門
> ## 目次
* **CHAPTER 01 Gitが必要な理由を知ろう**
	* 01 バージョン管理はなぜ必要？
	* 02 GitHub Desktopをインストールする
	* 03 Visual Studio Codeをインストールする
	* 04 Gitの基本的なしくみを理解する
* **CHAPTER 02 GitHub Desktopでローカルのファイルを管理しよう**
	* 01 ローカルリポジトリを作成する
	* 02 変更を「コミット」する
	* 03 コミットを取り消す
	* 04 Markdownの書き方を覚える
	* 05 VSCodeの「ソース管理」機能を利用する
* **CHAPTER 03 GitHubのリモートリポジトリで共有しよう**
	* 01 リモートリポジトリとGitHub
	* 02 リモートリポジトリを作って共同作業の準備をする
	* 03 共同作業でファイルを編集する
	* 04 共有したくないファイルを無視させる
* **CHAPTER 04 コンフリクトとブランチを理解しよう**
	* 01 コンフリクトとブランチ
	* 02 コンフリクトを解決する
	* 03 ブランチを作って作業分担する
	* 04 ブランチをマージする
	* 05 ブランチを削除する
* **CHAPTER 05 GitHubの便利な機能を利用しよう**
	* 01 Gitの機能とGitHubの機能
	* 02 プライベートリポジトリにする
	* 03 プルリクエストを使ってマージする
	* 04 イシューを使って問題を解決する
	* 05 その他の便利な機能
* **CHAPTER 06 コマンドラインを利用しよう**
	* 01 Gitはコマンドラインでも利用できる
	* 02 ローカルリポジトリを利用する
	* 03 リモートリポジトリを利用する
	* 04 コンフリクト解決とブランチを利用する
	* 05 プルリクエストを利用する
<br>


<!-- CHAPTER 01 Gitが必要な理由を知ろう -->
> ### CHAPTER 01 Gitが必要な理由を知ろう
<div style="margin-left: 20px">

#### 01 バージョン管理はなぜ必要？
</div>
<div style="margin-left: 40px">

**Git：** エンジニア向けのバージョン管理システム
**GitHub：** Gitを利用したインターネット上のサービス
<br>


**＜Gitクライアント＞**
| アプリ名        | 種類 | 解説                                                                               |
|----------------|------|------------------------------------------------------------------------------------|
| git            | CUI  | Git公式から配布されている。<br>単独のアプリではなくLinuxやmacOSのターミナルから利用する。 |
| Git Bash       | CUI  | Git for Windowsというプロジェクトが配布している。<br>Windows用のアプリ。               |
||||
| GitHub Desktop | GUI  | GitHubが配布しているアプリ。<br>昨日は限定的だが軽く覚えやすい。                        |
| SourceTree     | GUI  | アトラシアン社が配布しているアプリ。多機能                                             |
</div>

<br>

<div style="margin-left: 20px">

#### 02 GitHub Desktopをインストールする
</div>
<div style="margin-left: 40px">

**<u>① GitHubアカウントを作成</u>**
[・GitHub（英語サイト）](https://github.com/)

**[Point]**
　Gitのユーザー名とGitHubのユーザー名は別にすることもできる。
　（ややこしいので合わせることをお勧め）

**<u>② GitHub Desktopをインストール</u>**
[・GitHub Desktopのインストールサイト](https://desktop.github.com )

**<u>③ GitHub の料金プラン</u>**
| プラン      | 概要 |
|------------|--|
| Free       | 公開／非公開を問わずリポジトリの数に制限はなく、<br>複数ユーザーで管理できる組織アカウント(Organization)も利用可能 |
| Team       | 利用可能な容量などが増加 |
| Enterprise | 自社専用のGitHubサーバーを持つことができる |
| GitHub One | 最上位のプラン。サポートなどが強化 |

[GitHubの料金プラン案内ページ](https://github.com/pricing)

**<u>[COLUMN] GitHubのヘルプ</u>**
　[GitHubヘルプ](https://help.github.com/ja)
　※料金支払い設定の変更など、GitHubの使い方で分からないことはGitHubヘルプで調べることができる。
　　GitHub Desktopのヘルプもこの中にある。
</div>
<br>


<div style="margin-left: 20px">

#### 03 Visual Studio Codeをインストールする
</div>
<div style="margin-left: 40px">

**<u>① Gitと相性のいいテキストエディタ</u>**
Gitと連携する機能を持つ<mark>Visual Studio Code（VSCode）</mark>を紹介

**<u>② VSCodeのインストール</u>**
[VSCodeのダウンロードサイト](https://code.visualstudio.com)

**<u>③ コマンドラインのGitをインストール</u>**
[Gitの公式サイト](https://git-scm.com)

</div>
<br>


<div style="margin-left: 20px">

#### 04 Gitの基本的なしくみを理解する
</div>
<div style="margin-left: 40px">

**<u>① ただのフォルダを「リポジトリ化」する</u>**
Gitを利用するには、PC内のフォルダを"保管庫"を意味する<mark>リポジトリ</mark>に変える。
リポジトリ化すると、フォルダ内に<mark>「.git」</mark>という名前の隠しフォルダが作られる。
この「.gitフォルダ」が<mark>リポジトリの本体</mark>。



</div>



<br><br>

<!-- CHAPTER 02 GitHub Desktopでローカルのファイルを管理しよう -->
> ### CHAPTER 02 GitHub Desktopでローカルのファイルを管理しよう
<div style="margin-left: 20px">

#### 01 ローカルリポジトリを作成する
</div>
<div style="margin-left: 40px">

`...一旦省略...`


</div>



<br>
<div style="margin-left: 20px">

#### 02 変更を「コミット」する</div>
</div>
<div style="margin-left: 40px">

`...一旦省略...`


</div>



<br>
<div style="margin-left: 20px">

#### 03 コミットを取り消す
</div>
<div style="margin-left: 40px">

`...一旦省略...`


</div>



<br>
<div style="margin-left: 20px">

#### 04 Markdownの書き方を覚える
</div>
<div style="margin-left: 40px">

`...一旦省略...`


</div>



<br>
<div style="margin-left: 20px">

#### 05 VSCodeの「ソース管理」機能を利用する
</div>
<div style="margin-left: 40px">

`...一旦省略...`


</div>





<br><br>

<!-- CHAPTER 03 GitHubのリモートリポジトリで共有しよう -->
> ### CHAPTER 03 GitHubのリモートリポジトリで共有しよう
<div style="margin-left: 20px">

#### 01 リモートリポジトリとGitHub
</div>
<div style="margin-left: 40px">

`...一旦省略...`



</div>


<br>
<div style="margin-left: 20px">

#### 02 リモートリポジトリを作って共同作業の準備をする
</div>
<div style="margin-left: 40px">

**<u>① ローカルリポジトリ ⇒ リモートリポジトリを作成</u>**
　リモートリポジトリを作成する方法には次の2通りがある。

$\quad$**1. 「ローカルリポジトリ」⇒「リモートリポジトリ」を作成**
　　　GitHub Desktopの<mark>パブリッシュ機能</mark>で、
　　　「作成済みのローカルリポジトリ」から「リモートリポジトリ」を作成。

$\quad$**2. 「リモートリポジトリ」⇒「ローカルリポジトリ」を作成**
　　　GitHub上で「リモートリポジトリ」を作成し、
　　　「ローカルリポジトリ」は<mark>クローン</mark>という機能で作成。
<br>

$\quad$<font color="Red">「Fetch(フェッチ)」</font>は<u>リモートリポジトリの状態を確認</u>する操作。
$\quad$ リモートリポジトリのURLは **「https:\/\/github.com\/ユーザー名\/リポジトリ名」** という形式になる。
<br>

**<u>② リポジトリのさまざまなページ</u>**

**＜リポジトリページのタブ＞**
| タブ | 説明 |
|--|--|
| Issues             | 掲示板のようなもので、作業中に相談したいものなどを書き込む |
| Pull requests      | 共同作業をスムーズに行うために使用する |
| Actions            | CI/CD(継続的開発／配布)という開発手法で使用する |
| Packages、Releases | 完成した成果物(アプリなど)を配布するときに使用する |
| Projects           |  |
| Wiki               | チームで利用するドキュメントを作成する |
| Security           | セキュリティ上の警告が表示される |
| Insights           | リポジトリに対する統計情報が表示される |
| Settings           | リポジトリの設定を行う |

<br>

**<u>③ GitHub上でリモートリポジトリを確認する</u>**
<br><br>


$\quad$**<u>[COLUMN] GitHub上でリモートリポジトリを作成する</u>**
$\quad$ページ右上部の＜＋＞ボタンをクリック＜New Repository＞を選択。
$\quad$作成画面が表示されるので、必要な項目を入力して＜Create repository＞をクリック。
$\quad$※設定項目のほとんどはローカルリポジトリの作成と同様。
<br>


**<u>④ リモートリポジトリからローカルリポジトリを作成する</u>**
共同作業するメンバーは、<mark>クローン</mark>という操作を行ってローカルリポジトリを用意する。
　※以降は、リポジトリを作成したユーザーとは**別のユーザー**を使用。
　※第1章で解説したインストールやユーザー設定などはひと通り完了した状態。

`...クローン操作は一旦省略...`

※クローン完了した時点では<font color="red">まだリモートリポジトリにプッシュできない。</font>
※そのためには<mark>コラボレーター設定</mark>といものが必要となる。
<br>


**<u>④ READMEを作成する</u>**

**【前提】**
　最初にリモートリポジトリを作成したユーザーでGitHubのページを表示する。
　(この時点では他のユーザーはこのリポジトリを操作できない)

**【概要】**
　＜CODE＞タブの下部に**＜Add a README＞**というボタンが配置されている。
　この<mark>README</mark>の実態は、リポジトリ直下に保存された<u>README.md</u>というMarkdownファイルで、
　入力しておくと<font color="red">リポジトリのトップに表示される。</font>

**【READMEの作成】**

$\quad$`...作成操作は一旦省略...`

$\quad$作成を完了すると、それまで＜Add a README＞が表示されていた部分にREADMEが表示される。

**【追加したREADMEをローカルリポジトリにプルして確認】**
$\quad$現状はGitHub Desktopに**＜Fetch origin＞**と表示されている。
$\quad$＜Fetch origin＞をクリックすると**＜Pull origin＞**に変わる。

$\quad$※<font color="red">「Fetch(フェッチ)」</font>は<u>リモートリポジトリの状態を確認</u>する操作。
$\quad$$\quad$⇒この操作によってまだプルしていないコミットが見つかったら**＜Pull origin＞**となる。
$\quad$※ GitHub Desktopは定期的にフェッチを実行するので、
$\quad$$\quad$クリックする前から＜Pull origin＞と表示されていることもある。

</div>



<br>
<div style="margin-left: 20px">

#### 03 共同作業でファイルを編集する
</div>
<div style="margin-left: 40px">

**<u>① コラボレーターを設定する</u>**
$\quad$パブリックのリポジトリは、<font color="blue">誰でも</font><mark>クローン</mark>や<mark>プル</mark>することが<font color="blue">できる</font>。
$\quad$ただし、<mark>プッシュ</mark>は<font color="red">できない</font>。

$\quad$この状態でコミットをプッシュしようとすると、以下のように表示される。
$\quad$・「Want to create a fork?（フォークを作成したいですか？）」
$\quad$・「Do you want to fork this repository?（このリポジトリをフォークしたいですか？）」

$\quad$※<font color="red">「フォーク(fork)」</font>とは、他人のリモートリポジトリを複製して自分のリモートリポジトリを作ること。

$\quad$リモートリポジトリの所有者<font color="red">以外</font>のユーザーが<mark>プッシュ</mark>できるようにするには、
$\quad$<mark><font color="red">「コラボレーター（共同編集者）」</font></mark>に設定する必要がある。
$\quad$(これは公開も非公開のリポジトリもまったく同じ)

**【コラボレーターの招待を開始する】**
$\quad$`...操作の詳細は省略...`

$\quad$以下は操作の流れ
$\quad$**【所有者側】**
$\quad$$\quad$(1) ＜Settings＞タブのサイドメニューから **Collaborators** をクリック
$\quad$$\quad$(2) アクセス確認画面でメール送信で本人確認を行う。
$\quad$$\quad$(3) 招待ページ下部の **＜Invite a collaborator＞ボタン** をクリック
$\quad$$\quad$(4) コラボレーター選択画面で、招待したいユーザー名を入力し **＜Add ～＞ボタン** をクリック
$\quad$$\quad$(5) 招待ページ下部に**招待したユーザーが追加**される。
$\quad$$\quad$※この時点ではユーザー名の隣に **「Pending Invite(招待保留)」** と表示されており、まだ招待は完了していない。

$\quad$**【招待者側】**
$\quad$$\quad$(1) 招待メールの**＜View Invitation＞ボタン**をクリック
$\quad$$\quad$(2) 確認のWebページが表氏されるので**＜Accept Invitation＞ボタン**をクリック
$\quad$$\quad$(3) リポジトリが表示される

$\quad$これで招待されたユーザーもプッシュができるようになる。


</div>



<br>
<div style="margin-left: 20px">

#### 04 共有したくないファイルを無視させる
</div>
<div style="margin-left: 40px">

**<u>① .gitignoreファイルを作成する</u>**
$\quad$`...一旦省略...`


**<u>② .gitignoreファイルを編集する</u>**
$\quad$`...一旦省略...`


**<u>③ GitHub上のサンプルを参考にする</u>**
$\quad$`...一旦省略...`
$\quad$[.gitignoreのサンプル](https://github.com/github/gitignore)





</div>





<br><br>

<!-- CHAPTER 04 コンフリクトとブランチを理解しよう -->
> ### CHAPTER 04 コンフリクトとブランチを理解しよう
<div style="margin-left: 20px">

#### 01 コンフリクトとブランチ
</div>
<div style="margin-left: 40px">

**<u>① コンフリクトとは</u>**
$\quad$`...一旦省略...`


**<u>② ブランチとは</u>**
$\quad$`...一旦省略...`





</div>



<br>
<div style="margin-left: 20px">

#### 02 コンフリクトを解決する
</div>
<div style="margin-left: 40px">

**<u>① コンフリクトをわざと引き起こす</u>**
$\quad$`...一旦省略...`


**<u>② コンフリクトを解決する</u>**
$\quad$`...一旦省略...`

$\quad$**コンフリクトの対処法**
$\quad$・現在の変更を取り込む$\quad$：Accept Current &nbsp;&nbsp;&nbsp;Change
$\quad$・入力側の変更を取り込む ：Accept Incoming Change
$\quad$・両方の変更を取り込む$\quad$：Accept Both &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Change
$\quad$・変更の比較$\quad$$\quad$$\quad$$\quad$$\quad$&nbsp;：$\quad$$\quad$&nbsp;&nbsp;&nbsp;&nbsp;Compare Changes







</div>



<br>
<div style="margin-left: 20px">

#### 03 ブランチを作って作業分担する
</div>
<div style="margin-left: 40px">

**<u>① ブランチを作る</u>**
$\quad$`...一旦省略...`

$\quad$**GitHub Desktop**
$\quad$＜Current branch＞⇒＜New branch＞⇒｛ブランチの名前を入力｝
$\quad$$\quad$⇒＜Create branch＞⇒新しいブランチに切り替わる

**<u>② ブランチを切り替える</u>**
$\quad$`...一旦省略...`







</div>



<br>
<div style="margin-left: 20px">

#### 04 ブランチをマージする
</div>
<div style="margin-left: 40px">

**<u>① さまざまなマージの使い方</u>**
$\quad$`...一旦省略...`

$\quad$(1) 本家のコミットを分家に取り込んで状態を合わせる
$\quad$(2) 分家のブランチを本家のブランチに統合する

**<u>② mainブランチのコミットを取り込む</u>**
$\quad$`...一旦省略...`

$\quad$(1) 本家のコミットを分家に取り込んで状態を合わせる
$\quad$$\quad$**GitHub Desktop**
$\quad$$\quad$・取り込む側のブランチに切り替える（ここではedit_submanual）
$\quad$$\quad$・＜Branch＞⇒＜Update from main＞を選択するとmainブランチのコミットが取り込まれる
$\quad$$\quad$※＜Update from main＞はmainブランチから他のブランチへの取り込みにしか使えない


**<u>③ 他のブランチをmainブランチに取り込む</u>**
$\quad$`...一旦省略...`

$\quad$(2) 分家のブランチを本家のブランチに統合する
$\quad$$\quad$**GitHub Desktop**
$\quad$$\quad$・mainブランチに切り替える
$\quad$$\quad$・＜Branch＞⇒＜Merge into current branch＞を選択
$\quad$$\quad$・「Merge into main」画面で、取り込むブランチを選択（ここではedit_submanual）
$\quad$$\quad$・＜Merge edit_submanual into main＞をクリック
$\quad$$\quad$・分家ブランチのコミットがmainブランチに取り込まれる


$\quad$$\quad$**[マージとリベース]**
$\quad$$\quad$`...一旦省略...`






</div>



<br>
<div style="margin-left: 20px">

#### 05 ブランチを削除する
</div>
<div style="margin-left: 40px">

**<u>① ブランチを削除する</u>**
$\quad$`...一旦省略...`


**<u>② リモートリポジトリからブランチを削除する</u>**
$\quad$`...一旦省略...`









</div>





<br><br>

<!-- CHAPTER 05 GitHubの便利な機能を利用しよう -->
> ### CHAPTER 05 GitHubの便利な機能を利用しよう
<div style="margin-left: 20px">

#### 01 Gitの機能とGitHubの機能
</div>
<div style="margin-left: 40px">

**<u>① どこまでがGitの機能？</u>**
$\quad$`...一旦省略...`


**<u>② GitHubが提供してくれる機能</u>**
$\quad$`...一旦省略...`

$\quad$<font color="red">パブリック</font>：リモートリポジトリを誰でも見られるように公開する
$\quad$<font color="red">プライベート</font>：所有者(オーナー)と共同作業者(コラボレーター)しか見られないように非公開にする

$\quad$<font color="red">プルリクエスト</font>：ブランチのマージをする前にインターネット上で相談／確認を行う対話環境を提供する機能
$\quad$$\quad$$\quad$$\quad$$\quad$$\quad$$\quad$&nbsp;&nbsp;見た目は掲示板に似ており、ファイルの変更部分を分かりやすく示す機能などが用意

$\quad$<font color="red">イシュー</font>：簡単にいえば相談用の掲示板。バグ報告や共同作業者が作業場の相談を行うなど



</div>



<br>
<div style="margin-left: 20px">

#### 02 プライベートリポジトリにする
</div>
<div style="margin-left: 40px">

**<u>① プライベートリポジトリを作るには</u>**
$\quad$`...一旦省略...`

$\quad$**プライベートリポジトリをゼロから作る**
$\quad$$\quad$(1) ローカルリポジトリをパブリッシュするときに＜Keep this code private＞にチェックを入れる（p.75）
$\quad$$\quad$(2) GitHub上でリポジトリを作成するときに＜Private＞を選ぶ（P.75）



**<u>② 作成済みのパブリックリポジトリをプライベートにする</u>**
$\quad$`...一旦省略...`

$\quad$**[手順]**
$\quad$・所有者がGitHub上で、対象リポジトリの＜Settings＞ページを表示
$\quad$・サイドメニューの＜Option＞ページの最下部にある＜Danger Zone＞という項目を表示
$\quad$・＜Danger Zone＞内の＜Make private＞をクリック
$\quad$・簡単に変更できないようにいくつかの確認画面が表示される
$\quad$・完了すると、リポジトリページの上部に＜Private＞と表示される

<br>

$\quad$**プライベート化すると使えなくなる機能**
| 機能 | 機能概要 |
|--|--|
stars<br>watchers | 注目するリポジトリに付ける印
pages | リポジトリにプッシュしたHTMLやCSSを使ってWebサイトを公開する機能
Wiki | 

$\quad$など
<br>

$\quad$**＜Danger Zone＞で行える設定**
|  |  |
|--|--|
Make this repository private | パブリッシュリポジトリのプライベート化
Transfer ownership | リポジトリの所有権を他のユーザーに委譲
Archive this repository | リポジトリを読み取り専用にする
Delete this repository | リポジトリの削除

<br>

$\quad$**GitHubのプラン変更**
$\quad$**[手順]**
$\quad$・GitHubのユーザー設定画面を表示する（リポジトリの設定画面ではない）
$\quad$$\quad$画面右上部のユーザーアイコンをクリックし、＜Settings＞を選択
$\quad$・サイドメニューから＜Billing＞をクリック
$\quad$・＜Subscriptions＞タブから＜Update＞ボタンをクリック




</div>



<br>
<div style="margin-left: 20px">

#### 03 プルリクエストを使ってマージする
</div>
<div style="margin-left: 40px">

**<u>① プルリクエストとは</u>**
$\quad$`...一旦省略...`


**<u>② プルリクエスト用のブランチを作成する</u>**
$\quad$`...一旦省略...`


**<u>③ ブルリクエストを作成する</u>**
$\quad$`...一旦省略...`


**<u>④ ファイルの変更をレビューする</u>**
$\quad$`...一旦省略...`


**<u>⑤ レビューに対応する</u>**
$\quad$`...一旦省略...`


**<u>⑥ レビューして変更を承認する</u>**
$\quad$`...一旦省略...`


**<u>⑦ プルリクエストをマージする</u>**
$\quad$`...一旦省略...`








</div>



<br>

#### 04 イシューを使って問題を解決する
</div>
<div style="margin-left: 40px">

**<u>① イシューは問題解決ツール</u>**
$\quad$`...一旦省略...`


**<u>② イシューを使って相談する</u>**
$\quad$`...一旦省略...`


**<u>③ イシューに気づいてもらいやすくする</u>**
$\quad$`...一旦省略...`


**<u>④ その他のイシューの便利な機能</u>**
$\quad$`...一旦省略...`







</div>



<br>
<div style="margin-left: 20px">

#### 05 その他の便利な機能
</div>
<div style="margin-left: 40px">

**<u>① </u>**
$\quad$`...一旦省略...`


**<u>② </u>**
$\quad$`...一旦省略...`


**<u>③ </u>**
$\quad$`...一旦省略...`


**<u>④ </u>**
$\quad$`...一旦省略...`


**<u>⑤ </u>**
$\quad$`...一旦省略...`






</div>





<br><br>

<!-- CHAPTER 06 コマンドラインを利用しよう -->
> ### CHAPTER 06 コマンドラインを利用しよう
<div style="margin-left: 20px">

#### 01 Gitはコマンドラインでも利用できる
</div>
<div style="margin-left: 40px">

**<u>① gitとGit Bash</u>**
$\quad$Gitはコマンドラインでも利用できる。
$\quad$本書では、GitをWindowsで実行するために<mark>Git Bash</mark>を利用する。
$\quad$(Git BashはWindows上でLinuxコマンドを利用可能にするコマンドラインツール)
<br>

**<u>② GitHub Desktopで作成したリポジトリを利用してみる</u>**
$\quad$GitHub Desktopで作成したリポジトリをgitコマンドで確認する。

$\quad$**【手順】GitHub Desktopの標準シェル(コマンドラインツール)をGit Bashに設定**
$\quad$$\quad$・＜File＞⇒＜Options＞を選択する
$\quad$$\quad$・サイドメニューから＜Integrations＞を選択する
$\quad$$\quad$・「Shell」プルダウンから＜Git Bash＞を選択する
$\quad$$\quad$・＜Save＞をクリックする
$\quad$$\quad$※GitHub Desktop経由からGit Bashを起動すると、
$\quad$$\quad$$\quad$ローカルリポジトリのフォルダに移動した状態で起動できる。


$\quad$**【手順】GitHub DesktopからGit Bashを起動**
$\quad$$\quad$・＜Repository＞⇒＜Open in Git Bash＞を選択する


$\quad$$\quad$<mark>git statusコマンド</mark>
$\quad$$\quad$ ・現在の状態を確認する。
$\quad$$\quad$ ・GitHub Desktopの＜Changes＞タブに相当。

<div style="margin-left: 60px">

```
＜実行結果＞
$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
```
※コミットしていない変更がないため、「nothing to commit」と表示される。
</div>


$\quad$$\quad$<mark>git logコマンド</mark>
$\quad$$\quad$ ・コミットの履歴を確認する。
$\quad$$\quad$ ・GitHub Desktopの＜History＞タブに相当。
$\quad$$\quad$ ・git logコマンドの結果は1画面に表示しきれないため、１画面分表示したら最後に「:」が表示される。
$\quad$$\quad$ 　[ ↑ ] [ ↓ ] キーでスクロールすることができ、[Q]キーで表示を終了する。
<div style="margin-left: 60px">

```
＜実行結果＞
$ git log
commit 6d176ec342d3bb1a59655e963f3f71d853906a67 (HEAD -> main, origin/main, origin/HEAD)
Author: sn455 <252955943+sn455@users.noreply.github.com>
Date:   Tue Jan 27 09:26:53 2026 +0900

    sakura.pngを更新

commit 657dba064243c671f0aa294bd753d2d9c0dfd0bb
Author: sn455 <252955943+sn455@users.noreply.github.com>
Date:   Tue Jan 27 09:26:16 2026 +0900

    sakura.pngを作成

commit e2b9a712003f2b108b67c79b24d2ca643883c169
Author: sn455 <shingo.numoto@j-tech.jp>
Date:   Tue Jan 27 09:20:08 2026 +0900

    manual.mdのリンクを修正

～～～～～～～～～～～～～～～～ 中略 ～～～～～～～～～～～～～～～～～～～～～～～

commit 2a123418bcdc6d245766530b9820d0e6b100b4cd
Author: sn455 <shingo.numoto@j-tech.jp>
Date:   Wed Jan 21 09:22:41 2026 +0900

    マニュアル作成スタート

commit cc724dc16d25284a5a3423db5468132cea7bed43
Author: sn455 <shingo.numoto@j-tech.jp>
Date:   Wed Jan 21 08:59:59 2026 +0900

    Initial commit
```
</div>








</div>



<br>
<div style="margin-left: 20px">

#### 02 ローカルリポジトリを利用する
</div>
<div style="margin-left: 40px">

**<u>① ローカルリポジトリを作成する</u>**
$\quad$<mark>git initコマンド</mark>
$\quad$ ・ローカルリポジトリを作成する。
$\quad$ ・GitHub Desktopの＜Create a new repository＞画面に相当する操作。
$\quad$ ・リポジトリ化するフォルダを作成し、その中に移動してから git initコマンドを実行する。

<div style="margin-left: 40px">

```
＜実行結果＞
$ mkdir OfficeWorkManual2	# リポジトリ化するフォルダを作成
$ cd OfficeWorkManual2	# 作成したフォルダへ移動
$ git init		# git initコマンドでリポジトリ化
  Initialized empty Git repository in C:/Users/010159_numoto/Prac/GitPrac/OneDayGit/sn455/OfficeWorkManual2/.git/
```
※GitHub Desktopと異なり .gitattibutesは作成されないため、必要ならテキストエディタで作成してコミットする。
</div>


**<u>② 変更をコミットする</u>**
$\quad$VSCodeでフォルダを開き、ファイル（manual\.md）を作成して上書き保存する。

$\quad$<mark>git statusコマンド</mark>
$\quad$ ・現在の状態を確認する。
$\quad$ ・GitHub Desktopの＜Changes＞タブに相当。

$\quad$<mark>git addコマンド</mark>
$\quad$ ・追加可能なファイルをコミット対象にする。
$\quad$ ・`-Aオプション`は、追加可能なすべてのファイルをコミット対象にする。
$\quad$ ・1ファイルずつ対象を指定したい場合は<font color="red">「git add {ファイル名}」</font>とする。
$\quad$ ・GitHub Desktopの＜Changes＞タブに表示されているファイルにチェックを入れる操作に相当する。

$\quad$$\quad$**[POINT]**
$\quad$$\quad$ ・git addコマンドによってコミット対象にすることを<font color="red">「ステージング」</font>
$\quad$$\quad$ ・コミット対象のファイルが存在する仮想上の場所のことを<font color="red">「ステージングエリア」</font>
$\quad$$\quad$ ・逆にコミット対象から外したいときは<font color="red">「git rmコマンド」</font>を実行

$\quad$<mark>git diff --cachedコマンド</mark>
$\quad$ ・差分を確認する。
$\quad$ ・`--cachedオプション`は、コミット対象(ステージングエリア)の差分を表示することを意味する。
$\quad$ ・

$\quad$<mark>git commitコマンド</mark>
$\quad$ ・コミットを実行する
$\quad$ ・`-mオプション`を付けた場合はそのあとに「"(ダブルクォート)」で囲んでコミットメッセージを入力する。
$\quad$ ・

<div style="margin-left: 40px">

```ini
＜実行結果＞
$ git status			# 現在の状態を確認
  On branch master
  
  No commits yet
  
  Untracked files:			# ⇐ステージングされていないファイル
    (use "git add <file>..." to include in what will be committed)
          manual.md
  
  nothing added to commit but untracked files present (use "git add" to track)

$ git add -A			# 追加可能なすべてのファイルをステージングする

$ git status			# 再度、現在の状態を確認
  On branch master
  
  No commits yet
  
  Changes to be committed:		# ⇐コミット対象となったファイル
    (use "git rm --cached <file>..." to unstage)
          new file:   manual.md

$ git diff --cached		# コミット対象の差分を確認
  diff --git a/manual.md b/manual.md
  new file mode 100644
  index 0000000..b028f4b
  --- /dev/null
  +++ b/manual.md
  @@ -0,0 +1,9 @@
  +# 事務マニュアル
  +## 休日出勤について
  +## 経費の精算について
  +## 宅配便の発送について
  +## 電話、来客対応について
  +## ゴミ収集について
  +## プリンタについて
  +### プリンタドライバのインストール
  +## 大容量データの送受信について

$ git commit -m "マニュアル作成スタート" # コミットを実行
  [master (root-commit) c55ef90] マニュアル作成スタート
   1 file changed, 9 insertions(+)
   create mode 100644 manual.md

$ git log			# コミット履歴を確認
commit c55ef902fbd5f8f780c66ea5cabb88228ef7cefe (HEAD -> master)
Author: sn455 <252955943+sn455@users.noreply.github.com>
Date:   Tue Jan 27 11:41:26 2026 +0900

    マニュアル作成スタート
```
</div>









**<u>③ コミットを取り消す</u>**
$\quad$`...一旦省略...`








</div>



<br>
<div style="margin-left: 20px">

#### 03 リモートリポジトリを利用する
</div>
<div style="margin-left: 40px">

**<u>① </u>**
$\quad$`...一旦省略...`


**<u>② </u>**
$\quad$`...一旦省略...`


**<u>③ </u>**
$\quad$`...一旦省略...`


**<u>④ </u>**
$\quad$`...一旦省略...`


**<u>⑤ </u>**
$\quad$`...一旦省略...`






</div>



<br>
<div style="margin-left: 20px">

#### 04 コンフリクト解決とブランチを利用する
</div>
<div style="margin-left: 40px">

**<u>① </u>**
$\quad$`...一旦省略...`


**<u>② </u>**
$\quad$`...一旦省略...`


**<u>③ </u>**
$\quad$`...一旦省略...`


**<u>④ </u>**
$\quad$`...一旦省略...`


**<u>⑤ </u>**
$\quad$`...一旦省略...`






</div>



<br>
<div style="margin-left: 20px">

#### 05 プルリクエストを利用する
</div>
<div style="margin-left: 40px">

**<u>① </u>**
$\quad$`...一旦省略...`


**<u>② </u>**
$\quad$`...一旦省略...`


**<u>③ </u>**
$\quad$`...一旦省略...`


**<u>④ </u>**
$\quad$`...一旦省略...`


**<u>⑤ </u>**
$\quad$`...一旦省略...`






</div>





