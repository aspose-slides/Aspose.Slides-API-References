---
title: HttpRequestCachePolicy()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância.
type: docs
weight: 79
url: /pt/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | O comportamento de cache para recursos. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla o comportamento de cache para recursos. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Uma quantidade de tempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla o comportamento de cache para recursos. |
| maxAge | [TimeSpan](../../../system/timespan/) | A idade máxima permitida para recursos. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Uma quantidade de tempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | O momento em que os recursos armazenados no cache devem ser revalidados. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) construtor

Constrói uma nova instância.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla o comportamento de cache para recursos. |
| maxAge | [TimeSpan](../../../system/timespan/) | A idade máxima permitida para recursos. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Uma quantidade de tempo. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | O momento em que os recursos armazenados no cache devem ser revalidados. |

## Veja Também

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Classe [HttpRequestCachePolicy](../)
* Classe [TimeSpan](../../../system/timespan/)
* Classe [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Biblioteca [Aspose.Slides](../../../)