---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый экземпляр.
type: docs
weight: 79
url: /ru/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Поведение кэширования для ресурсов. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Управляет поведением кэширования для ресурсов. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Продолжительность. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Управляет поведением кэширования для ресурсов. |
| maxAge | [TimeSpan](../../../system/timespan/) | Максимальный допустимый возраст ресурсов. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Продолжительность. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Время, когда ресурсы, хранящиеся в кэше, должны быть повторно проверены. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) конструктор

Создает новый экземпляр.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Управляет поведением кэширования для ресурсов. |
| maxAge | [TimeSpan](../../../system/timespan/) | Максимальный допустимый возраст ресурсов. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Продолжительность. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Время, когда ресурсы, хранящиеся в кэше, должны быть повторно проверены. |

## Смотрите также

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)