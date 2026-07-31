---
title: ReadContentAsBinHex()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang didekodekan dari BinHex.
type: docs
weight: 456
url: /id/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode


Membaca konten dan mengembalikan byte biner yang didekodekan dari BinHex.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer tempat menyalin teks yang dihasilkan. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat mulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembalian

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)