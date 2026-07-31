---
title: ReadContentAsBase64()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang didekodekan Base64.
type: docs
weight: 755
url: /id/system.xml/xmlreader/readcontentasbase64/
---
## XmlReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Membaca konten dan mengembalikan byte biner yang telah didekodekan Base64.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer tempat menyalin teks yang dihasilkan. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat memulai penyalinan hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembali

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)