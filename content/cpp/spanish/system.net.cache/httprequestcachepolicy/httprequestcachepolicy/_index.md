---
title: HttpRequestCachePolicy()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 79
url: /es/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | El comportamiento de caché de los recursos. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla el comportamiento de caché de los recursos. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Una cantidad de tiempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla el comportamiento de caché de los recursos. |
| maxAge | [TimeSpan](../../../system/timespan/) | La edad máxima permitida para los recursos. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Una cantidad de tiempo. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | El momento en que los recursos almacenados en la caché deben volver a validarse. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) constructor

Construye una nueva instancia.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Controla el comportamiento de caché de los recursos. |
| maxAge | [TimeSpan](../../../system/timespan/) | La edad máxima permitida para los recursos. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Una cantidad de tiempo. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | El momento en que los recursos almacenados en la caché deben volver a validarse. |

## Ver también

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Clase [HttpRequestCachePolicy](../)
* Clase [TimeSpan](../../../system/timespan/)
* Clase [DateTime](../../../system/datetime/)
* Espacio de nombres [System::Net::Cache](../../)
* Biblioteca [Aspose.Slides](../../../)