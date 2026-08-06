# UMIGURI_charts

## これはなに？
かなすらUMIGURI部の活動拠点になります
キャラクターや称号、譜面を追加して俺たちのUMIGURIを作り上げよう！

## 導入手順
### 1.インストール
### 1.1gitを導入する
以下のサイトからgitをインストールしてください。インストーラーはnext連打でそのままインストールしてもらって大丈夫です。
https://gitforwindows.org/

### 1.2 github desktopをインストールする
以下のサイトからgithub desktopをインストールしてください。これがあるとGitの操作性が格段に向上します
https://docs.github.com/ja/desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop

### 2.クローン準備
UMIGURI上のdataフォルダを開き、中身をすべて削除する※

> [!WARNING]
> 自作の譜面やキャラクターのデータがある場合は必ずそれらを退避してからフォルダを削除するようにしてください
> キャラクターやネームプレートなどの初期データは構築後復活しますが、サンプルの楽曲のデータはリポジトリに含めていない関係で戻らないので、残したい方はそちらもあらかじめ退避しておいてください

### 3.クローン
3.1 github desktopを起動して、左上から`file>clone a repository`を選択

3.2 URLタブに移動して上部の入力欄に以下を入力
`https://github.com/mitsuhira/UMIGURI_charts.git`

3.3 Local pathに自分のdataファイルの場所を入力

3.4 cloneボタンを押下

## 4.確認
もともと空だったdataフォルダに先ほど削除したものと同名のフォルダが追加されたら成功

## 譜面を追加するには
1.自分のgit環境を最新の状態に更新する
github desktop上部の`Repository>pull`

2.コミットするファイルを選ぶ
画面左に変更もしくは追加候補のファイルが表示されるので追加したいものにチェックを入れる(作りかけだったり追加したくないファイルはチェックを外してください)

3.Summaryに更新内容を記載してから`Commit to main`押下

4.github desktop上部の`Repository>push`でファイルをプッシュする
