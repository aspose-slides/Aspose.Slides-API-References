---
title: HttpRequestCacheLevel
second_title: Referensi API Aspose.Slides untuk C++
description: Enum ini menjelaskan pengaturan cache untuk HTTP.
type: docs
weight: 40
url: /id/system.net.cache/httprequestcachelevel/
---
## HttpRequestCacheLevel enum

Enum ini menjelaskan pengaturan cache untuk HTTP.

```cpp
enum class HttpRequestCacheLevel
```

### Nilai

| Name | Value | Description |
| --- | --- | --- |
| Default | 0 | Memenuhi permintaan untuk sebuah sumber daya baik dengan menggunakan salinan yang di-cache dari sumber daya tersebut atau dengan mengirimkan permintaan untuk sumber daya ke server. |
| BypassCache | 1 | Memenuhi permintaan dengan menggunakan server. |
| CacheOnly | 2 | Selalu menggunakan cache klien untuk mendapatkan sumber daya. |
| CacheIfAvailable | 3 | Memenuhi permintaan untuk sumber daya dari cache jika sumber daya tersedia, jika tidak mengirimkan permintaan ke server. |
| Revalidate | 4 | Menggunakan salinan lokal sumber daya jika cap waktu klien sama dengan cap waktu sumber daya di server. Jika tidak, sumber daya diunduh dari server. |
| Reload | 5 | Sebuah sumber daya selalu diunduh dari server. |
| NoCacheNoStore | 6 | Tidak pernah memenuhi permintaan dengan menggunakan sumber daya dari cache dan tidak menyimpan sumber daya di cache. |
| CacheOrNextCacheOnly | 7 | Memenuhi permintaan untuk sebuah sumber daya baik dari cache komputer lokal atau dari cache remote di LAN. |
| Refresh | 8 | Memenuhi permintaan dengan menggunakan server atau cache selain cache lokal. |

## Lihat Juga

* Ruang nama [System::Net::Cache](../)
* Perpustakaan [Aspose.Slides](../../)