garoon Utility for JavaScript
==============
# Overview
garoon Utility for JavaScriptはサイボウズ ガルーンのSOAP APIにアクセスするJavaScript ライブラリです。  
SOAP APIのリクエストやレスポンスをjson形式で取り扱うことができます。

## Desctiption
* Garoon on cybozu.com に対応します。
* SOAP APIの扱えるバージョンであればオンプレ版ガルーンでも動作しますがテストはしていません。
* 下記アプリケーションに対応しています
  * ベース(Base)
  * スケジュール(Schedule)
* SOAP APIリファレンス
  * [Garoon(ガルーン) API](https://cybozudev.zendesk.com/hc/ja/articles/202228424) 
* APIアクセスの度に、ログイン名およびパスワードをプレーンテキストでサーバーに送信しています。セキュリティを確保するためには、SSLをご利用ください。
* 本ライブラリはサポートの対象外です。
* 質問がある場合はcybozu developer networkの[コミュニティ](https://cybozudev.zendesk.com/hc/ja/community/topics/200674863-Garoon-API-%E3%83%95%E3%82%A9%E3%83%BC%E3%83%A9%E3%83%A0)をご活用ください。

## Requirement
* 以下の JavaScript ライブラリに依存しています。
  * [jQuery](http://jquery.com/) v3.1.1

## Usage
* 各クラスの参照は [リファレンス](https://github.com/north-river/garoonUtlity/wiki)を参考にしてください。
* [Tips](https://cybozudev.zendesk.com/hc/ja/articles/115001805783)

## VS.
[cybozu-connect](https://github.com/hatashinya/cybozu-connect)との相違点は以下です。
 * kintoneやガルーンカスタマイズ時に利用する想定で、各関数をカスタマイズJSから参照しやすい形に変更しています。（内部的な変更であり利用の仕方自体に変わりはありません。）

## License
MIT License

## Copyright
Copyright(c) Cybozu, Inc.
