---
title: ReadContentAsBinHex()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang didekode BinHex.
type: docs
weight: 781
url: /id/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

Membaca konten dan mengembalikan byte biner yang telah didekode **BinHex**.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer tempat menyalin teks yang dihasilkan. Nilai ini tidak dapat **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat mulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke dalam buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembali

Jumlah byte yang ditulis ke buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)