# mcoding-standard-layout

[「HTML5/CSS3モダンコーディング フロントエンドエンジニアが教える3つの本格レイアウト」](http://www.shoeisha.co.jp/book/detail/9784798141572)
のスタンダードレイアウトをコーディングしたリポジトリです。

## Build

このプロジェクトをビルドするためには[node.js](https://nodejs.org/en/)と[gulp](http://gulpjs.com/)が必要です。
あらかじめインストールしておいてください。

インストールが終わったら、以下のコマンドを実行してビルドしてください。

```
git clone git@github.com:shgtkshruch/mcoding-standard-layout.git
cd mcoding-standard-layout
npm install
gulp build
```

以上のコマンドを実行すると、`dist`フォルダにビルドされたファイルが生成されます。

完成したWebページを閲覧する方法は２つあります。
- `dist`フォルダのなかの`index.html`をブラウザで開く
- `gulp build`コマンドを打ってローカルサーバーを立ち上げ、ブラウザで`http://localhost:3000`にアクセスする

以上、どちらかの方法でWebページを閲覧してください。
