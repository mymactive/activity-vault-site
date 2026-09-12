# activity-vault-site

個人用Androidアプリ「活動ログ / ActivityVault」の紹介サイトです。紹介ページ、プライバシーポリシー、利用についての説明を掲載します。

## GitHub Pagesの初回設定

リポジトリの **Settings → Pages → Build and deployment** で、次を選んで保存します。

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

公開予定URLは [活動ログの紹介サイト](https://mymactive.github.io/activity-vault-site/) です。Pagesで公開が完了したことと、各ページがログインなしで開くことを確認してから利用してください。

## ファイル

- `index.html`: 紹介ページ
- `privacy.html`: プライバシーポリシー
- `terms.html`: 利用について
- `styles.css`: 共通の表示設定
- `.nojekyll`: HTML/CSSをそのまま配信するための設定

ビルドやパッケージのインストールは不要です。Pages設定後はmainへの変更が公開へ反映されます。

このリポジトリには説明用の静的ファイルを置きます。健康記録、アプリの個人設定、署名鍵、Google認証情報は追加しないでください。
