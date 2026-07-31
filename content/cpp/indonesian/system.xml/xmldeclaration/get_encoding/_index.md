---
title: get_Encoding()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan tingkat enkoding dokumen XML.
type: docs
weight: 14
url: /id/system.xml/xmldeclaration/get_encoding/
---
## XmlDeclaration::get_Encoding() metode

Mengembalikan tingkat enkoding dokumen XML.

```cpp
String System::Xml::XmlDeclaration::get_Encoding()
```

### Nilai Kembali

Nama enkoding karakter yang valid.

## Keterangan

Nama enkoding karakter yang paling umum didukung untuk XML adalah sebagai berikut:

| Kategori | Nama Enkoding |
| --- | --- |
| Unicode | UTF-8, UTF-16 |
| ISO 10646 | ISO-10646-UCS-2, ISO-10646-UCS-4 |
| ISO 8859 | ISO-8859-n (where "n" is a digit from 1 to 9) |
| JIS X-0208-1997 | ISO-2022-JP, Shift_JIS, EUC-JP |

Nilai ini bersifat opsional. Jika nilai tidak diatur, metode ini mengembalikan [String::Empty](../../../system/string/empty/). Jika atribut enkoding tidak disertakan, enkoding UTF-8 diasumsikan ketika dokumen ditulis atau disimpan.

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlDeclaration](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)