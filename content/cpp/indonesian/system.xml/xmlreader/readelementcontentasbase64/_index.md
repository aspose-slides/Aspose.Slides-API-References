---
title: ReadElementContentAsBase64()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca elemen dan mendekode konten Base64.
type: docs
weight: 768
url: /id/system.xml/xmlreader/readelementcontentasbase64/
---
## XmlReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode

Membaca elemen dan mendekode konten **Base64**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer yang akan menyalin teks hasil. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer di mana mulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke dalam buffer. Jumlah byte sebenarnya yang disalin dikembalikan oleh metode ini. |

### Nilai Kembalian

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)