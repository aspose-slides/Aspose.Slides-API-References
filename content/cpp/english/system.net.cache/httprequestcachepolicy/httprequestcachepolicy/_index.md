---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 79
url: /system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | The caching behavior for resources. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controls the caching behavior for resources. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | An amount of time. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controls the caching behavior for resources. |
| maxAge | [TimeSpan](../../../system/timespan/) | The max age permitted for resources. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | An amount of time. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | The time when resources stored in the cache must be revalidated. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) constructor


Constructs a new instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controls the caching behavior for resources. |
| maxAge | [TimeSpan](../../../system/timespan/) | The max age permitted for resources. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | An amount of time. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | The time when resources stored in the cache must be revalidated. |

## See Also

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)