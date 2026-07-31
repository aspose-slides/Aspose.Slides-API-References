---
title: ReadContentAsBinHex()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca konten dan mengembalikan byte biner yang didekodekan dari BinHex.
type: docs
weight: 599
url: /id/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metode

Membaca konten dan mengembalikan byte biner yang didekodekan dari BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer yang akan diisi dengan teks hasil. Nilai ini tidak dapat menjadi **nullptr**. |
| index | **int32_t** | Offset dalam buffer di mana mulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum byte yang akan disalin ke dalam buffer. Jumlah byte yang sebenarnya disalin dikembalikan oleh metode ini. |

### Nilai Kembali

Jumlah byte yang ditulis ke dalam buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlValidatingReader](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)