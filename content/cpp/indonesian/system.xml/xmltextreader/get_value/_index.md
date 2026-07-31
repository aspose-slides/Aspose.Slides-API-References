---
title: get_Value()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai teks dari node saat ini.
type: docs
weight: 79
url: /id/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() metode

Mengembalikan nilai teks dari node saat ini.

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### Nilai Kembalian

Nilai yang dikembalikan tergantung pada nilai [XmlTextReader::get_NodeType](../get_nodetype/) node.

## Keterangan

Tabel berikut mencantumkan tipe node yang memiliki nilai untuk dikembalikan. Semua tipe node lainnya mengembalikan [String::Empty](../../../system/string/empty/). 

| Node Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nilai atribut. |
| CDATA| Konten bagian CDATA. |
| Comment| Konten komentar. |
| DocumentType| Subset internal. |
| ProcessingInstruction| Seluruh konten, tidak termasuk target. |
| SignificantWhitespace| Spasi putih dalam ruang lingkup `xml:space='preserve'`. |
| [Text](../../../system.text/)| Konten node teks. |
| Whitespace| Spasi putih di antara markup. |
| [XmlDeclaration](../../xmldeclaration/)| Konten deklarasi. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)