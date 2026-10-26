---
title: RequestCacheLevel
second_title: Referensi API Aspose.Slides untuk C++
description: Enum ini menjelaskan pengaturan cache yang berlaku untuk setiap WebRequest.
type: docs
weight: 27
url: /id/system.net.cache/requestcachelevel/
---
## RequestCacheLevel enum


The enum describes cache settings applicable for any [WebRequest](../../system.net/webrequest/).

```cpp
enum class RequestCacheLevel
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | 0 | Memenuhi permintaan untuk sumber daya baik dengan menggunakan salinan yang di-cache dari sumber daya tersebut atau dengan mengirimkan permintaan ke server. |
| BypassCache | 1 | Memenuhi permintaan dengan menggunakan server. Tidak ada entri yang diambil dari cache. |
| CacheOnly | 2 | Memenuhi permintaan untuk sumber daya hanya dari cache. WebException akan dilemparkan ketika sumber daya tidak ada di cache klien. |
| CacheIfAvailable | 3 | Memenuhi permintaan untuk sumber daya dari cache jika sumber daya tersedia, jika tidak mengirimkan permintaan ke server. |
| Revalidate | 4 | Menggunakan salinan lokal sumber daya jika stempel waktu klien sama dengan stempel waktu sumber daya di server. Jika tidak, sumber daya diunduh dari server. |
| Reload | 5 | Sumber daya selalu diunduh dari server. |
| NoCacheNoStore | 6 | Tidak pernah memenuhi permintaan dengan menggunakan sumber daya dari cache dan tidak menyimpan sumber daya di cache. |

## Lihat Juga

* Ruang Nama [System::Net::Cache](../)
* Perpustakaan [Aspose.Slides](../../)