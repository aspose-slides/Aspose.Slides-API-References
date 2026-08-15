---
title: RequestCacheLevel
second_title: Aspose.Slides for C++ API 參考
description: 此列舉描述適用於任何 WebRequest 的快取設定。
type: docs
weight: 27
url: /zh-hant/system.net.cache/requestcachelevel/
---
## RequestCacheLevel 列舉


此列舉描述適用於任何 [WebRequest](../../system.net/webrequest/) 的快取設定。

```cpp
enum class RequestCacheLevel
```

### Values

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Default | 0 | 透過使用資源的快取副本或向伺服器發送資源請求來滿足對資源的請求。 |
| BypassCache | 1 | 透過使用伺服器來滿足請求。不會從快取中取得任何項目。 |
| CacheOnly | 2 | 僅從快取中滿足對資源的請求。當資源不在客戶端快取時，將拋出 WebException。 |
| CacheIfAvailable | 3 | 若資源可用，則從快取中滿足對資源的請求，否則向伺服器發送請求。 |
| Revalidate | 4 | 若客戶端時間戳與伺服器上資源的時間戳相同，則使用資源的本機副本。否則，從伺服器下載資源。 |
| Reload | 5 | 資源始終從伺服器下載。 |
| NoCacheNoStore | 6 | 永不使用快取中的資源滿足請求，且不會快取資源。 |

## See Also

* 命名空間 [System::Net::Cache](../)
* 程式庫 [Aspose.Slides](../../)