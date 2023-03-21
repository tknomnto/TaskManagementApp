# メッセージボード

## 概要
個人学習を目的として開発したメッセージボード

## 使用言語/技術
- Node.js
- EJS
- SQLite

## 機能

## 日記
### 2023年2月16日
- EJSを使用し、index.ejsでHTMLの内容が表示されるようにした
- cssを適用させるためにscript.js内でルーティングの処理を行った
- other.ejsを作成し、複数ページの処理を行ってみた

### 2023年3月10日
- クエリパラメータを使用したページ間のデータのやり取りを行った
- フォーム送信を通してGETとPOSTのアクセスの分岐を作成した
- 表によるデータの表示を行った（グローバルなデータ）
- クッキーを使用したデータの表示を行った（ユーザ特有のデータ）

### 2023年3月21日
- 簡単なメッセージボードの作成を行った
- ログインページ：IDの入力によってIDを設定できる
- メインページ：メッセージを残すことができる
- 最大メッセージ数は10個（それ以上は古いものから削除）
- 今回はテキストファイルにデータを保存するようになっている
