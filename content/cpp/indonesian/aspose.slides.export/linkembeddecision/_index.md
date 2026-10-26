---
title: LinkEmbedDecision
second_title: Aspose.Slides untuk C++ Referensi API
description: Menentukan bagaimana objek akan diproses selama penyimpanan.
type: docs
weight: 911
url: /id/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision enum

Menentukan bagaimana objek akan diproses selama penyimpanan.

```cpp
enum class LinkEmbedDecision
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Link | 0 | Objek akan disimpan secara eksternal, direferensikan oleh URL |
| Embed | 1 | Objek harus disematkan ke file yang dihasilkan jika memungkinkan. Jika penyematan tidak memungkinkan, GetUrl akan dipanggil dan, tergantung pada hasil, objek akan direferensikan oleh URL atau diabaikan. |
| Ignore | 2 | Objek akan diabaikan. |

## Lihat Juga

* Ruang Nama [Aspose::Slides::Export](../)
* Pustaka [Aspose.Slides](../../)