---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci.
type: docs
weight: 79
url: /cs/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Chování ukládání do mezipaměti pro zdroje. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Řídí chování ukládání do mezipaměti pro zdroje. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Množství času. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Řídí chování ukládání do mezipaměti pro zdroje. |
| maxAge | [TimeSpan](../../../system/timespan/) | Maximální povolený věk pro zdroje. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Množství času. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Čas, kdy musí být prostředky uložené v mezipaměti znovu ověřeny. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Řídí chování ukládání do mezipaměti pro zdroje. |
| maxAge | [TimeSpan](../../../system/timespan/) | Maximální povolený věk pro zdroje. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Množství času. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Čas, kdy musí být prostředky uložené v mezipaměti znovu ověřeny. |

## Viz také

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)