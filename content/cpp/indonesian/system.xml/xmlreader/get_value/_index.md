---
title: get_Value()
second_title: Referensi API Aspose.Slides untuk C++
description: Ketika ditimpa dalam kelas turunan, mengambil nilai teks dari node saat ini.
type: docs
weight: 92
url: /id/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() metode

Ketika ditimpa dalam kelas turunan, mengambil nilai teks dari node saat ini.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Nilai Kembalian

Nilai yang dikembalikan bergantung pada nilai [XmlReader::get_NodeType](../get_nodetype/) dari node.

## Keterangan

Tabel berikut mencantumkan tipe node yang memiliki nilai untuk dikembalikan. Semua tipe node lainnya mengembalikan [String::Empty](../../../system/string/empty/).

| Tipe node | Nilai |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| Nilai atribut. |
| `CDATA`| Konten bagian CDATA. |
| `Comment`| Konten komentar. |
| `DocumentType`| Subset internal. |
| `ProcessingInstruction`| Seluruh konten, kecuali target. |
| `SignificantWhitespace`| Spasi putih di antara markup dalam model konten campuran. |
| `[Text](../../../system.text/)`| Konten node teks. |
| `Whitespace`| Spasi putih di antara markup. |
| [XmlDeclaration](../../xmldeclaration/)| Konten deklarasi. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)