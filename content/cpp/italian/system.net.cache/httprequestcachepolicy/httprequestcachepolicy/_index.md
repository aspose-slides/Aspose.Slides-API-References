---
title: HttpRequestCachePolicy()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 79
url: /it/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Il comportamento di caching per le risorse. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controlla il comportamento di caching per le risorse. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Una quantità di tempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controlla il comportamento di caching per le risorse. |
| maxAge | [TimeSpan](../../../system/timespan/) | L'età massima consentita per le risorse. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Una quantità di tempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Il momento in cui le risorse memorizzate nella cache devono essere rivalutate. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) costruttore


Crea una nuova istanza.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controlla il comportamento di caching per le risorse. |
| maxAge | [TimeSpan](../../../system/timespan/) | L'età massima consentita per le risorse. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Una quantità di tempo. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Il momento in cui le risorse memorizzate nella cache devono essere rivalutate. |

## Vedi anche

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Classe [HttpRequestCachePolicy](../)
* Classe [TimeSpan](../../../system/timespan/)
* Classe [DateTime](../../../system/datetime/)
* Spazio dei nomi [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)