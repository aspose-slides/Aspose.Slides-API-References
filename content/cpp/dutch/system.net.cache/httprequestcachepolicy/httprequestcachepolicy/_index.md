---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar aan.
type: docs
weight: 79
url: /nl/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Het cache-gedrag voor bronnen. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Bepaalt het cache-gedrag voor bronnen. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Een hoeveelheid tijd. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Bepaalt het cache-gedrag voor bronnen. |
| maxAge | [TimeSpan](../../../system/timespan/) | De maximale leeftijd die voor bronnen is toegestaan. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Een hoeveelheid tijd. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Het moment waarop resources in de cache opnieuw gevalideerd moeten worden. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Bepaalt het cache-gedrag voor bronnen. |
| maxAge | [TimeSpan](../../../system/timespan/) | De maximale leeftijd die voor bronnen is toegestaan. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Een hoeveelheid tijd. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Het moment waarop resources in de cache opnieuw gevalideerd moeten worden. |

## Zie ook

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Klasse [HttpRequestCachePolicy](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Klasse [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Bibliotheek [Aspose.Slides](../../../)