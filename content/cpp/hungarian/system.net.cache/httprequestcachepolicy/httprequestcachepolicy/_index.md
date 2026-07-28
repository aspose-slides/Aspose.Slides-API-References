---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides C++ API referencia
description: Új példányt hoz létre.
type: docs
weight: 79
url: /hu/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Az erőforrások gyorsítótárazási viselkedése. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Az erőforrások gyorsítótárazási viselkedését szabályozza. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Egy időtartam. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Az erőforrások gyorsítótárazási viselkedését szabályozza. |
| maxAge | [TimeSpan](../../../system/timespan/) | Az erőforrások számára megengedett maximális életkor. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Egy időtartam. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Az az idő, amikor a gyorsítótárban tárolt erőforrásokat újra kell érvényesíteni. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) konstruktor


Új példányt hoz létre.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Az erőforrások gyorsítótárazási viselkedését szabályozza. |
| maxAge | [TimeSpan](../../../system/timespan/) | Az erőforrások számára megengedett maximális életkor. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Egy időtartam. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Az az idő, amikor a gyorsítótárban tárolt erőforrásokat újra kell érvényesíteni. |

## Lásd még

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)