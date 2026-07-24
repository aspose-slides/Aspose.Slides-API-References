---
title: HttpRequestCachePolicy()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 79
url: /tr/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Kaynaklar için önbellek davranışı. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kaynakların önbellek davranışını kontrol eder. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Bir zaman miktarı. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kaynakların önbellek davranışını kontrol eder. |
| maxAge | [TimeSpan](../../../system/timespan/) | Kaynaklar için izin verilen maksimum süre. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Bir zaman miktarı. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Önbellekte saklanan kaynakların yeniden doğrulanması gereken zaman. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Kaynakların önbellek davranışını kontrol eder. |
| maxAge | [TimeSpan](../../../system/timespan/) | Kaynaklar için izin verilen maksimum süre. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Bir zaman miktarı. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Önbellekte saklanan kaynakların yeniden doğrulanması gereken zaman. |

## İlgili

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Class [HttpRequestCachePolicy](../)
* Class [TimeSpan](../../../system/timespan/)
* Class [DateTime](../../../system/datetime/)
* Namespace [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)