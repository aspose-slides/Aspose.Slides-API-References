---
title: ReadContentAsBase64()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang didekodekan dari Base64.
type: docs
weight: 573
url: /id/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode

Membaca konten dan mengembalikan byte biner yang didekodekan dari Base64.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer yang akan diisi dengan teks hasil. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat memulai penyalinan hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke dalam buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembalian

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlValidatingReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)