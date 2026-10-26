---
title: HttpRequestCachePolicy()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 79
url: /fr/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Le comportement de mise en cache pour les ressources. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Contrôle le comportement de mise en cache pour les ressources. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Une durée. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Contrôle le comportement de mise en cache pour les ressources. |
| maxAge | [TimeSpan](../../../system/timespan/) | L'âge maximal autorisé pour les ressources. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Une durée. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | L'heure à laquelle les ressources stockées dans le cache doivent être revalidées. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Contrôle le comportement de mise en cache pour les ressources. |
| maxAge | [TimeSpan](../../../system/timespan/) | L'âge maximal autorisé pour les ressources. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Une durée. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | L'heure à laquelle les ressources stockées dans le cache doivent être revalidées. |

## Voir aussi

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)