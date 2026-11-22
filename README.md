# ServerMenu

Minecraft プラグイン ServerMenu 1.0.0 の稼働ファイルです。
Pterodactyl の `lobby_server` から 2026-11-22 に取得しました。

## 内容

- `plugins/ServerMenu-1.0.0.jar`: サーバーに配置されているプラグイン本体
- `plugins/ServerMenu/config.yml`: 現在の設定

元の Java ソースコードは確認できなかったため、このリポジトリには含めていません。
JAR の改変・再ビルドは行っていません。

## 導入

1. サーバーを停止します。
2. このリポジトリの `plugins/` の内容をサーバーの `plugins/` にコピーします。
3. `plugins/ServerMenu/config.yml` のワールド名やスポーン座標を確認します。
4. サーバーを起動します。

JAR の `plugin.yml` では API バージョン `1.21` が指定されています。

## コマンド・権限

- `/servermenu`: サーバーメニューを開く
- `/servermenu give`: メニューアイテムを付与
- `/servermenu reload`: 設定を再読み込み
- `servermenu.use`: 標準で全員に許可
- `servermenu.admin`: 標準で OP に許可

## SHA-256

```text
5a495bec8a514f4138b55fde15d361aba67a243d3122bcae7d7f3107e529e90a  plugins/ServerMenu-1.0.0.jar
a63b03f0618f06065373db7934e4fafe67c018a335f95cd3d8cddb6594aa5478  plugins/ServerMenu/config.yml
```
