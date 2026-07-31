---
title: get_LocalName()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama lokal node saat ini.
type: docs
weight: 27
url: /id/system.xml/xmlnodereader/get_localname/
---
## XmlNodeReader::get_LocalName() metode

Mengembalikan nama lokal node saat ini.

```cpp
String System::Xml::XmlNodeReader::get_LocalName() override
```

### Nilai Pengembalian

Nama node saat ini dengan awalan dihapus. Sebagai contoh, **LocalName** adalah **book** untuk elemen **<bk:book>**. Untuk tipe node yang tidak memiliki nama (seperti **[Text](../../../system.text/)**, **Comment**, dan seterusnya), metode ini mengembalikan [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)