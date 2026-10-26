---
title: ReadValueChunk()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca aliran teks besar yang disematkan dalam dokumen XML.
type: docs
weight: 807
url: /id/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) metode

Membaca aliran teks besar yang disematkan dalam dokumen XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Array karakter yang berfungsi sebagai buffer tempat isi teks ditulis. Nilai ini tidak boleh **nullptr**. |
| index | **int32_t** | Offset dalam buffer tempat [XmlReader](../) dapat mulai menyalin hasil. |
| count | **int32_t** | Jumlah maksimum karakter yang akan disalin ke dalam buffer. Jumlah sebenarnya karakter yang disalin dikembalikan oleh metode ini. |

### Nilai Kembalian

Jumlah karakter yang dibaca ke dalam buffer. Nilai nol dikembalikan ketika tidak ada lagi isi teks.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlReader](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)