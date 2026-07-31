---
title: get_Value()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan nilai teks dari node saat ini.
type: docs
weight: 79
url: /id/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() metode

Mengembalikan nilai teks dari node saat ini.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Nilai Kembalian

Nilai yang dikembalikan tergantung pada [XmlNodeReader::get_NodeType](../get_nodetype/) node.

## Keterangan

Tabel berikut mencantumkan jenis node yang memiliki nilai untuk dikembalikan. Semua jenis node lainnya mengembalikan [String::Empty](../../../system/string/empty/). 

| Jenis Node | Nilai |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nilai atribut. |
| CDATA| Isi dari bagian CDATA. |
| Comment| Isi komentar. |
| DocumentType| Subset internal. |
| ProcessingInstruction| Seluruh isi, tidak termasuk target. |
| SignificantWhitespace| Spasi putih di antara markup dalam model konten campuran. |
| [Text](../../../system.text/)| Isi node teks. |
| Whitespace| Spasi putih di antara markup. |
| [XmlDeclaration](../../xmldeclaration/)| Isi deklarasi. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeReader](../)
* Ruang Nama [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)