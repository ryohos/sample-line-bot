# sample-line-bot

LINE向けチャットボット作成用のサンプルコード

## 説明

LINE向けチャットボットのサンプルです。
サーバーにはHerokuを使用しています。

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

* heroku上にデプロイされます。
* Redisは追加されません。自身での追加をお願いします。

*DOCOMOの雑談対話APIでのやりとりを記憶するためにRedisを使用しています。*

## 環境変数

下記の環境変数を設定してください。


|項目|説明|
|:--|:--|
|LINE_CHANNEL_ACCESS_TOKEN|Messaging APIを使用するために必要なAccess Tokenを設定してください。|
|BOT_MODE|Botのモードです。DOCOMOと設定するとDOCOMOの雑談対話APIを使用するモードになります。|
|DOCOMO_CHAT_API_KEY|DOCOMOの雑談対話APIを使用するために必要なAPI Keyを設定してください。|
|REDIS_URL|RedisのURLです。HerokuアプリでAdd-Onを追加した際に自動的に設定されます。|

## ライセンス

MITライセンスです。

