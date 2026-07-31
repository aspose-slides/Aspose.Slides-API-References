---
title: ReadChars()
second_title: Referensi API Aspose.Slides untuk C++
description: Membaca isi teks dari sebuah elemen ke dalam buffer karakter. Metode ini dirancang untuk membaca aliran teks tersemat yang besar dengan memanggilnya secara berurutan.
type: docs
weight: 755
url: /id/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metode

Membaca isi teks dari sebuah elemen ke dalam buffer karakter. Metode ini dirancang untuk membaca aliran teks tersemat yang besar dengan memanggilnya secara berurutan.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Array karakter yang berfungsi sebagai buffer tempat isi teks ditulis. |
| index | **int32_t** | Posisi dalam **buffer** di mana metode dapat mulai menulis isi teks. |
| count | **int32_t** | Jumlah karakter yang akan ditulis ke dalam **buffer**. |

### Nilai Kembalian

Jumlah karakter yang dibaca. Nilai ini dapat menjadi 0 jika pembaca tidak berada pada sebuah elemen atau jika tidak ada lagi isi teks yang dapat dikembalikan dalam konteks saat ini.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)