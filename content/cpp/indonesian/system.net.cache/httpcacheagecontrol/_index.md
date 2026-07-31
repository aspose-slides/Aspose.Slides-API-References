---
title: HttpCacheAgeControl
second_title: Referensi API Aspose.Slides untuk C++
description: CacheAgeControl digunakan untuk menentukan preferensi terkait usia item yang di-cache dan kesegarannya.
type: docs
weight: 53
url: /id/system.net.cache/httpcacheagecontrol/
---
## HttpCacheAgeControl enum

CacheAgeControl digunakan untuk menentukan preferensi terkait usia item yang di-cache dan kesegarannya.

```cpp
enum class HttpCacheAgeControl
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| None | 0 | Hanya untuk penggunaan internal. |
| MinFresh | 1 | Konten dapat diambil dari cache jika sisa waktu sebelum kedaluwarsa lebih besar dari atau sama dengan waktu yang ditentukan dengan nilai ini. |
| MaxAge | 2 | Konten dapat diambil dari cache sampai usianya lebih tua dari usia yang ditentukan dengan nilai ini. |
| MaxStale | 4 | Konten dapat diambil dari cache setelah kedaluwarsa sampai waktu yang ditentukan dengan nilai ini berakhir. |
| MaxAgeAndMinFresh | 3 | MaxAge and MinFresh. |
| MaxAgeAndMaxStale | 6 | MaxAge and MaxStale. |

## Lihat Juga

* Ruang Nama [System::Net::Cache](../)
* Perpustakaan [Aspose.Slides](../../)