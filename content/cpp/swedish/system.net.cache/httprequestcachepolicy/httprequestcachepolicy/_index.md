---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans.
type: docs
weight: 79
url: /sv/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Cachebeteendet för resurser. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Styr cachebeteendet för resurser. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | En tidsmängd. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Styr cachebeteendet för resurser. |
| maxAge | [TimeSpan](../../../system/timespan/) | Den maximala åldern som tillåts för resurser. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | En tidsmängd. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Tiden då resurser lagrade i cachen måste valideras på nytt. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) konstruktor


Skapar en ny instans.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Styr cachebeteendet för resurser. |
| maxAge | [TimeSpan](../../../system/timespan/) | Den maximala åldern som tillåts för resurser. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | En tidsmängd. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Tiden då resurser lagrade i cachen måste valideras på nytt. |

## Se även

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Klass [HttpRequestCachePolicy](../)
* Klass [TimeSpan](../../../system/timespan/)
* Klass [DateTime](../../../system/datetime/)
* Namnrymd [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)