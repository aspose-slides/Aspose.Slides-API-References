---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API 参考
description: 构造一个新实例。
type: docs
weight: 79
url: /zh/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | 资源的缓存行为。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制资源的缓存行为。 |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | 一段时间。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制资源的缓存行为。 |
| maxAge | [TimeSpan](../../../system/timespan/) | 资源允许的最大年龄。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 一段时间。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 缓存中存储的资源必须重新验证的时间。 |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) 构造函数

构造一个新实例。

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | 控制资源的缓存行为。 |
| maxAge | [TimeSpan](../../../system/timespan/) | 资源允许的最大年龄。 |
| freshOrStale | [TimeSpan](../../../system/timespan/) | 一段时间。 |
| cacheSyncDate | [DateTime](../../../system/datetime/) | 缓存中存储的资源必须重新验证的时间。 |

## 另请参见

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)