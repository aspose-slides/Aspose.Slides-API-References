---
title: ReadContentAsBase64()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang telah didekode Base64.
type: docs
weight: 638
url: /id/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) method


Membaca konten dan mengembalikan byte biner yang telah didekode **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer tempat menyalin teks hasil. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat memulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Pengembalian

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)