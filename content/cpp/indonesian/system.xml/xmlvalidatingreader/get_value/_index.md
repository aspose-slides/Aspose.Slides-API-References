---
title: get_Value()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai teks dari node saat ini.
type: docs
weight: 79
url: /id/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() metode

Mengembalikan nilai teks dari node saat ini.

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### Nilai Kembalian

Nilai yang dikembalikan tergantung pada XmlValidatingReader::NodeType dari node tersebut.

## Keterangan

Tabel berikut menampilkan tipe node yang memiliki nilai untuk dikembalikan. Semua tipe node lainnya mengembalikan [String::Empty](../../../system/string/empty/). 

| Tipe Node | Nilai |
| --- | --- |
| [Attribute](../../../system/attribute/) | Nilai atribut. |
| CDATA | Konten bagian CDATA. |
| Comment | Konten komentar. |
| DocumentType | Subset internal. |
| ProcessingInstruction | Seluruh konten, kecuali target. |
| SignificantWhitespace | Spasi putih di antara markup dalam model konten campuran. |
| [Text](../../../system.text/) | Konten node teks. |
| Whitespace | Spasi putih di antara markup. |
| [XmlDeclaration](../../xmldeclaration/) | Konten deklarasi. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlValidatingReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)