---
title: HttpCacheAgeControl
second_title: Aspose.Slides for C++ API 参考
description: CacheAgeControl 用于指定关于缓存项年龄和新鲜度的偏好。
type: docs
weight: 53
url: /zh/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl 枚举


CacheAgeControl 用于指定关于缓存项年龄和新鲜度的偏好。

```cpp
enum class HttpCacheAgeControl
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 仅供内部使用。 |
| MinFresh | 1 | 如果在过期前剩余的时间大于或等于此值指定的时间，则可以从缓存中获取内容。 |
| MaxAge | 2 | 内容可以从缓存中获取，直到其年龄大于此值指定的时间为止。 |
| MaxStale | 4 | 内容在过期后，直到此值指定的时间过去为止，都可以从缓存中获取。 |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## 另请参阅

* 命名空间 [System::Net::Cache](../)
* 库 [Aspose.Slides](../../)