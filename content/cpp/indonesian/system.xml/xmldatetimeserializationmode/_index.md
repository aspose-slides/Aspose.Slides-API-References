---
title: XmlDateTimeSerializationMode
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan bagaimana memperlakukan nilai waktu saat mengkonversi antara string dan DateTime.
type: docs
weight: 781
url: /id/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum

Menentukan bagaimana memperlakukan nilai waktu saat mengkonversi antara string dan [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Local | 0 | Diperlakukan sebagai waktu lokal. Jika objek [DateTime](../../system/datetime/) mewakili Coordinated Universal Time (UTC), itu dikonversi menjadi waktu lokal. |
| Utc | 1 | Diperlakukan sebagai UTC. Jika objek [DateTime](../../system/datetime/) mewakili waktu lokal, itu dikonversi menjadi UTC. |
| Unspecified | 2 | Diperlakukan sebagai waktu lokal jika [DateTime](../../system/datetime/) sedang dikonversi menjadi string. Jika string sedang dikonversi menjadi [DateTime](../../system/datetime/), konversi menjadi waktu lokal jika zona waktu ditentukan. |
| RoundtripKind | 3 | Informasi zona waktu harus dipertahankan saat mengkonversi. |

## Lihat Juga

* Ruang Nama [System::Xml](../)
* Perpustakaan [Aspose.Slides](../../)