---
title: get_LocalName()
second_title: Referensi API Aspose.Slides untuk C++
description: Ketika dioverride dalam kelas turunan, mengambil nama lokal dari node saat ini.
type: docs
weight: 40
url: /id/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metode


Ketika dioverride dalam kelas turunan, mengambil nama lokal dari node saat ini.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Nilai Kembali

Nama node saat ini dengan prefix dihapus. Misalnya, **LocalName** adalah **book** untuk elemen **<bk:book>**. Untuk tipe node yang tidak memiliki nama (seperti **[Text](../../../system.text/)**, **Comment**, dan sebagainya), metode ini mengembalikan [String::Empty](../../../system/string/empty/).

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)