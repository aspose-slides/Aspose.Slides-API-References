---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama terkualifikasi dari node saat ini.
type: docs
weight: 14
url: /id/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() metode

Mengembalikan nama terkualifikasi dari node saat ini.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```

### Nilai Kembalian

Nama terkualifikasi dari node saat ini. Sebagai contoh, **Name** adalah **bk:book** untuk elemen **<bk:book>**.

## Catatan

Nama yang dikembalikan bergantung pada XmlValidatingReader::NodeType dari node. Tipe node berikut mengembalikan nilai yang terdaftar. Semua tipe node lainnya mengembalikan string kosong. 

| Tipe Node | Nama |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nama atribut. |
| DocumentType| Nama tipe dokumen. |
| Element| Nama tag. |
| EntityReference| Nama entitas yang dirujuk. |
| ProcessingInstruction| Target dari instruksi pemrosesan. |
| [XmlDeclaration](../../xmldeclaration/)| String literal `xml`. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlValidatingReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)