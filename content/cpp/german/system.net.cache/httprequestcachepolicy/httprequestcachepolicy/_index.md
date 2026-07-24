---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 79
url: /de/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Das Caching-Verhalten für Ressourcen. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Steuert das Caching-Verhalten für Ressourcen. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Eine Zeitspanne. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Steuert das Caching-Verhalten für Ressourcen. |
| maxAge | [TimeSpan](../../../system/timespan/) | Das maximal zulässige Alter für Ressourcen. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Eine Zeitspanne. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Der Zeitpunkt, zu dem im Cache gespeicherte Ressourcen neu validiert werden müssen. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) Konstruktor

Erstellt eine neue Instanz.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Steuert das Caching-Verhalten für Ressourcen. |
| maxAge | [TimeSpan](../../../system/timespan/) | Das maximal zulässige Alter für Ressourcen. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Eine Zeitspanne. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Der Zeitpunkt, zu dem im Cache gespeicherte Ressourcen neu validiert werden müssen. |

## Siehe auch

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Klasse [HttpRequestCachePolicy](../)
* Klasse [TimeSpan](../../../system/timespan/)
* Klasse [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Bibliothek [Aspose.Slides](../../../)