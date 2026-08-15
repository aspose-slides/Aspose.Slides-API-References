---
title: HttpRequestCacheLevel
second_title: Aspose.Slides C++ API 參考文件
description: 此列舉描述 HTTP 的快取設定。
type: docs
weight: 40
url: /zh-hant/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel 列舉


此列舉描述 HTTP 的快取設定。

```cpp
enum class HttpRequestCacheLevel
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Default | 0 | 透過使用該資源的快取副本或向伺服器發送資源請求，以滿足對資源的請求。 |
| BypassCache | 1 | 以使用伺服器的方式滿足請求。 |
| CacheOnly | 2 | 總是使用用戶端快取取得資源。 |
| CacheIfAvailable | 3 | 若快取中有該資源則從快取滿足請求，否則向伺服器發送請求。 |
| Revalidate | 4 | 若用戶端時間戳與伺服器上資源的時間戳相同，則使用資源的本地副本。否則，從伺服器下載資源。 |
| Reload | 5 | 資源始終從伺服器下載。 |
| NoCacheNoStore | 6 | 永不使用快取中的資源來滿足請求，且不會快取資源。 |
| CacheOrNextCacheOnly | 7 | 從本機電腦的快取或 LAN 上的遠端快取中滿足資源請求。 |
| Refresh | 8 | 透過使用伺服器或除本機快取之外的其他快取來滿足請求。 |

## 另請參閱

* 命名空間 [System::Net::Cache](../)
* 函式庫 [Aspose.Slides](../../)