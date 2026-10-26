---
title: HttpRequestCacheLevel
second_title: Aspose.Slides C++ API 参考
description: 该枚举描述了 HTTP 的缓存设置。
type: docs
weight: 40
url: /zh/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel 枚举

此枚举描述 HTTP 的缓存设置。

```cpp
enum class HttpRequestCacheLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | 通过使用资源的缓存副本或向服务器发送资源请求来满足对资源的请求。 |
| BypassCache | 1 | 通过使用服务器来满足请求。 |
| CacheOnly | 2 | 始终使用客户端缓存获取资源。 |
| CacheIfAvailable | 3 | 如果资源可用，则从缓存中满足对资源的请求；否则向服务器发送请求。 |
| Revalidate | 4 | 如果客户端时间戳与服务器上资源的时间戳相同，则使用资源的本地副本；否则从服务器下载资源。 |
| Reload | 5 | 资源始终从服务器下载。 |
| NoCacheNoStore | 6 | 永不通过使用缓存中的资源来满足请求，也不缓存资源。 |
| CacheOrNextCacheOnly | 7 | 通过本地计算机的缓存或局域网中的远程缓存来满足对资源的请求。 |
| Refresh | 8 | 通过使用服务器或除本地缓存之外的其他缓存来满足请求。 |

## 另请参见

* 命名空间 [System::Net::Cache](../)
* 库 [Aspose.Slides](../../)