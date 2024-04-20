Express, Prettier, ESLint の環境構築

`npm init -y`

Express のインストール
`npm i express`

ファイルを作成・編集して確認
`node index.js`

Prettier のインストール（公式ドキュメント確認）
`npm i --save-dev --save-exact prettier`

設定ファイルを作成（そこまで利用しない、VScode 拡張機能を利用）
`touch .prettierrc`

ESLint のインストール（対話形式で設定するのが楽）
設定はややこしいのでそこまで深追いしない...
`npm init @eslint/config`

nodemon もインストールしておく
`npm i nodemon`

package.json に nodemon 起動用のコマンドを利用して確認
`npm run ...`

Express
https://expressjs.com/

Prettier 設定
https://prettier.io/docs/en/options

ESlint 設定
https://eslint.org/docs/latest/use/configure/
