---
title: WebExceptionStatus
second_title: Aspose.Slides for C++ API 參考
description: 列舉 WebException 類別的狀態代碼。
type: docs
weight: 651
url: /zh-hant/system.net/webexceptionstatus/
---
## WebExceptionStatus 列舉


列舉 WebException 類別的狀態代碼。

```cpp
enum class WebExceptionStatus
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Success | 0 | 未發生錯誤。 |
| NameResolutionFailure | 1 | 名稱解析服務無法解析主機名稱。 |
| ConnectFailure | 2 | 無法在傳輸層級聯絡遠端服務點。 |
| ReceiveFailure | 3 | 未從遠端伺服器收到完整回應。 |
| SendFailure | 4 | 未能將完整請求傳送至遠端伺服器。 |
| PipelineFailure | 5 | 此請求為管線化請求，且連線在回應收到之前即已關閉。 |
| RequestCanceled | 6 | 請求已被取消或發生不可分類的錯誤。 |
| ProtocolError | 7 | 從伺服器收到的回應完整，但指示協定層級錯誤。 |
| ConnectionClosed | 8 | 連線過早關閉。 |
| TrustFailure | 9 | 無法驗證伺服器證書。 |
| SecureChannelFailure | 10 | 使用 SSL 建立連線時發生錯誤。 |
| ServerProtocolViolation | 11 | 伺服器回應不是有效的 HTTP 回應。 |
| KeepAliveFailure | 12 | 為指定 'Keep-Alive' 標頭的請求所建立的連線意外關閉。 |
| Pending | 13 | 內部非同步請求仍在等待中。 |
| Timeout | 14 | 在請求的逾時期間未收到回應。 |
| ProxyNameResolutionFailure | 15 | 名稱解析服務無法解析代理主機名稱。 |
| UnknownError | 16 | 發生未知類型的例外。 |
| MessageLengthLimitExceeded | 17 | 收到超過指定限制的訊息。 |
| CacheEntryNotFound | 18 | 找不到指定的快取項目。 |
| RequestProhibitedByCachePolicy | 19 | 請求未被快取政策允許。 |
| RequestProhibitedByProxy | 20 | 此請求未被代理允許。 |

## See Also

* 命名空間 [System::Net](../)
* 程式庫 [Aspose.Slides](../../)