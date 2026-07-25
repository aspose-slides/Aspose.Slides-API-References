---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ API リファレンス
description: WebException クラスのステータスコードを列挙します。
type: docs
weight: 651
url: /ja/system.net/webexceptionstatus/
---
## WebExceptionStatus 列挙型

WebException クラスのステータスコードを列挙します。

```cpp
enum class WebExceptionStatus
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Success | 0 | エラーは発生しませんでした。 |
| NameResolutionFailure | 1 | 名前解決サービスがホスト名を解決できませんでした。 |
| ConnectFailure | 2 | リモートサービスポイントにトランスポート層で接続できませんでした。 |
| ReceiveFailure | 3 | リモートサーバーから完全な応答が受信されませんでした。 |
| SendFailure | 4 | リモートサーバーへ完全なリクエストを送信できませんでした。 |
| PipelineFailure | 5 | リクエストはパイプライン化されたもので、応答が受信される前に接続が閉じられました。 |
| RequestCanceled | 6 | リクエストがキャンセルされたか、分類できないエラーが発生しました。 |
| ProtocolError | 7 | サーバーから受信した応答は完全でしたが、プロトコルレベルのエラーを示しています。 |
| ConnectionClosed | 8 | 接続が早期に閉じられました。 |
| TrustFailure | 9 | サーバー証明書を検証できませんでした。 |
| SecureChannelFailure | 10 | SSL を使用して接続を確立する際にエラーが発生しました。 |
| ServerProtocolViolation | 11 | サーバーの応答は有効な HTTP 応答ではありませんでした。 |
| KeepAliveFailure | 12 | 'Keep-Alive' ヘッダーを指定したリクエストの接続が予期せず閉じられました。 |
| Pending | 13 | 内部の非同期リクエストが保留中です。 |
| Timeout | 14 | リクエストのタイムアウト期間中に応答が受信されませんでした。 |
| ProxyNameResolutionFailure | 15 | 名前解決サービスがプロキシのホスト名を解決できませんでした。 |
| UnknownError | 16 | 不明なタイプの例外が発生しました。 |
| MessageLengthLimitExceeded | 17 | 指定された制限を超えるメッセージを受信しました。 |
| CacheEntryNotFound | 18 | 指定されたキャッシュエントリが見つかりませんでした。 |
| RequestProhibitedByCachePolicy | 19 | リクエストはキャッシュポリシーにより許可されませんでした。 |
| RequestProhibitedByProxy | 20 | このリクエストはプロキシにより許可されませんでした。 |

## 参照

* 名前空間 [System::Net](../)
* ライブラリ [Aspose.Slides](../../)