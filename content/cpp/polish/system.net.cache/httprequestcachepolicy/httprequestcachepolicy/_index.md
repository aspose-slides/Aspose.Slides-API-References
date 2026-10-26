---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy nową instancję.
type: docs
weight: 79
url: /pl/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Zachowanie buforowania zasobów. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kontroluje zachowanie buforowania zasobów. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Określona ilość czasu. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kontroluje zachowanie buforowania zasobów. |
| maxAge | [TimeSpan](../../../system/timespan/) | Maksymalny dopuszczalny wiek zasobów. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Określona ilość czasu. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Czas, w którym zasoby przechowywane w buforze muszą zostać ponownie zweryfikowane. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kontroluje zachowanie buforowania zasobów. |
| maxAge | [TimeSpan](../../../system/timespan/) | Maksymalny dopuszczalny wiek zasobów. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Określona ilość czasu. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Czas, w którym zasoby przechowywane w buforze muszą zostać ponownie zweryfikowane. |

## Zobacz także

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)