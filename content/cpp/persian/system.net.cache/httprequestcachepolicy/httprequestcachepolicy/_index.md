---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید می‌سازد.
type: docs
weight: 79
url: /fa/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | رفتار کش‌گذاری برای منابع. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | رفتار کش‌گذاری برای منابع را کنترل می‌کند. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | یک مقدار زمانی. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | رفتار کش‌گذاری برای منابع را کنترل می‌کند. |
| maxAge | [TimeSpan](../../../system/timespan/) | حداکثر سن مجاز برای منابع. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | یک مقدار زمانی. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | زمانی که منابع ذخیره‌شده در کش باید دوباره اعتبارسنجی شوند. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) سازنده

یک نمونه جدید می‌سازد.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | رفتار کش‌گذاری برای منابع را کنترل می‌کند. |
| maxAge | [TimeSpan](../../../system/timespan/) | حداکثر سن مجاز برای منابع. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | یک مقدار زمانی. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | زمانی که منابع ذخیره‌شده در کش باید دوباره اعتبارسنجی شوند. |

## موارد مرتبط

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)