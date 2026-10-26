---
title: ReadContentAsBinHex()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang telah didekode BinHex.
type: docs
weight: 664
url: /id/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode

Membaca konten dan mengembalikan byte biner yang telah didekode **BinHex**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer tempat menyalin teks hasil. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat memulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke buffer. Jumlah byte sebenarnya yang disalin dikembalikan oleh metode ini. |

### Nilai Kembalian

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)