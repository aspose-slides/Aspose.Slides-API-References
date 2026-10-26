---
title: ReadElementContentAsBase64()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca elemen dan mendekode konten Base64.
type: docs
weight: 651
url: /id/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode

Membaca elemen dan mendekode konten Base64.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer ke mana teks hasil akan disalin. Nilai ini tidak dapat **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat memulai penyalinan hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke dalam buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembali

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)