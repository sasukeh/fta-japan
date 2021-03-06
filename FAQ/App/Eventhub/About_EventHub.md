## はじめに
Azureには、EventHubというサービスがあります。
何かしらのイベントをメッセージとして受信したり送信することができます。
例えば下記の用途がその代表例です。

```
異常検出 (不正/外れ値)
アプリケーションのログ記録
クリックストリームなどの分析パイプライン
ライブ ダッシュボード
データのアーカイブ
トランザクション処理
ユーザー利用統計情報処理
デバイス利用統計情報ストリーミング
```

例えば、とあるデータをタイムリーに処理したいと思った場合、Webサーバー上のアプリケーションでも
ある程度は処理できると思います。そこで、拡張性や冗長性を保ちながらメッセージングの処理を行ったり
するためには、多くのことを考えなければなりません。そのため、EventHubではそういったデータ処理を一貫して処理できるような機能を提供しています。
また、IaaSではなくPaaSとしての提供ですので、お客様が運用を意識しなければならないコンポーネントは少なく、運用コストを下げることができます。

また、その他の機能として、AzureのObject Storageである`Azure Blob Storage`やAzureのData Lake Storageである
`Azure Data Lake Storage`にイベントをキャプチャーする`Event Hubs Capture`という機能があります。

<!-- 
## EventHubの概念
### コンシューマーグループ

### 

## EventHubの使い方
Azureのサービスですので、ポータルからでもCLI経由でもREST API経由でもデプロイできます。
ポータルが最も簡単なので、ポータルからデプロイします。

1. まず、リソースの作成をクリック
2. 検索窓に`EventHubs`と入力
3. 作成をクリック
4. 以下のように情報を入力
価格レベルですが、必要なコンシューマーグループと
-->

## EventHubの設定内容

## クライアントSDK

## Reference
- EventHub - Microsoft docs
https://docs.microsoft.com/ja-jp/azure/event-hubs/

-

- Azure Event Hubs との間でイベントを送受信する - .NET (Azure.Messaging.EventHubs)
https://docs.microsoft.com/ja-jp/azure/event-hubs/event-hubs-dotnet-standard-getstarted-send

