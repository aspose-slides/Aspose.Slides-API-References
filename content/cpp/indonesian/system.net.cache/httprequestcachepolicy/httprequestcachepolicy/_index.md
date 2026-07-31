---
title: HttpRequestCachePolicy()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 79
url: /id/system.net.cache/httprequestcachepolicy/httprequestcachepolicy/
---
## HttpRequestCachePolicy::HttpRequestCachePolicy() konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy()
```

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpRequestCacheLevel level)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| level | [HttpRequestCacheLevel](../../httprequestcachelevel/) | Perilaku caching untuk sumber daya. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan ageOrFreshOrStale)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Mengontrol perilaku caching untuk sumber daya. |
| ageOrFreshOrStale | [TimeSpan](../../../system/timespan/) | Jumlah waktu. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Mengontrol perilaku caching untuk sumber daya. |
| maxAge | [TimeSpan](../../../system/timespan/) | Usia maksimum yang diizinkan untuk sumber daya. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Jumlah waktu. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(DateTime cacheSyncDate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Waktu ketika sumber daya yang disimpan di cache harus divalidasi ulang. |

## HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl, TimeSpan, TimeSpan, DateTime) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Cache::HttpRequestCachePolicy::HttpRequestCachePolicy(HttpCacheAgeControl cacheAgeControl, TimeSpan maxAge, TimeSpan freshOrStale, DateTime cacheSyncDate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| cacheAgeControl | [HttpCacheAgeControl](../../httpcacheagecontrol/) | Mengontrol perilaku caching untuk sumber daya. |
| maxAge | [TimeSpan](../../../system/timespan/) | Usia maksimum yang diizinkan untuk sumber daya. |
| freshOrStale | [TimeSpan](../../../system/timespan/) | Jumlah waktu. |
| cacheSyncDate | [DateTime](../../../system/datetime/) | Waktu ketika sumber daya yang disimpan di cache harus divalidasi ulang. |

## Lihat Juga

* Enum [HttpRequestCacheLevel](../../httprequestcachelevel/)
* Enum [HttpCacheAgeControl](../../httpcacheagecontrol/)
* Kelas [HttpRequestCachePolicy](../)
* Kelas [TimeSpan](../../../system/timespan/)
* Kelas [DateTime](../../../system/datetime/)
* Ruang Nama [System::Net::Cache](../../)
* Library [Aspose.Slides](../../../)