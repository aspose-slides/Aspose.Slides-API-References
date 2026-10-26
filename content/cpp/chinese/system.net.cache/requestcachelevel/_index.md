---
title: RequestCacheLevel
second_title: Aspose.Slides for C++ API 参考
description: 该枚举描述适用于任何 WebRequest 的缓存设置。
type: docs
weight: 27
url: /zh/system.net.cache/requestcachelevel/
---
## RequestCacheLevel 枚举


该枚举描述适用于任何 [WebRequest](../../system.net/webrequest/) 的缓存设置。

```cpp
enum class RequestCacheLevel
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Default | 0 | 通过使用资源的缓存副本或向服务器发送资源请求来满足对资源的请求。 |
| BypassCache | 1 | 通过使用服务器来满足请求。不会从缓存中获取任何条目。 |
| CacheOnly | 2 | 仅从缓存中满足对资源的请求。当资源不在客户端缓存中时，将抛出 WebException。 |
| CacheIfAvailable | 3 | 如果资源可用，则从缓存中满足对资源的请求；否则向服务器发送请求。 |
| Revalidate | 4 | 如果客户端时间戳与服务器上资源的时间戳相同，则使用资源的本地副本。否则，从服务器下载资源。 |
| Reload | 5 | 始终从服务器下载资源。 |
| NoCacheNoStore | 6 | 永不使用缓存中的资源来满足请求，并且不缓存资源。 |

## 另见

* 命名空间 [System::Net::Cache](../)
* 库 [Aspose.Slides](../../)