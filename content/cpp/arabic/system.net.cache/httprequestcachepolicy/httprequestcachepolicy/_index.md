---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مثلاً جديدًا.
type: docs
weight: 79
url: /ar/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | سلوك التخزين المؤقت للموارد. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | يتحكم في سلوك التخزين المؤقت للموارد. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | مدة زمنية. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | يتحكم في سلوك التخزين المؤقت للموارد. |
| maxAge | [TimeSpan](../../../system/timespan/) | الحد الأقصى للعمر المسموح به للموارد. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | مدة زمنية. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | الوقت الذي يجب فيه إعادة التحقق من صحة الموارد المخزنة في التخزين المؤقت. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) منشئ

ينشئ مثلاً جديداً.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | يتحكم في سلوك التخزين المؤقت للموارد. |
| maxAge | [TimeSpan](../../../system/timespan/) | الحد الأقصى للعمر المسموح به للموارد. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | مدة زمنية. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | الوقت الذي يجب فيه إعادة التحقق من صحة الموارد المخزنة في التخزين المؤقت. |

## انظر أيضًا

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)