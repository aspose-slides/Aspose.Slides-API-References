---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama terkualifikasi dari node saat ini.
type: docs
weight: 14
url: /id/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() metode

Mengembalikan nama terkualifikasi dari node saat ini.

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```

### Nilai Kembali

Nama terkualifikasi dari node saat ini. Misalnya, **Name** adalah **bk:book** untuk elemen **<bk:book>**.

## Catatan

Nama yang dikembalikan bergantung pada nilai [XmlNodeReader::get_NodeType](../get_nodetype/) dari node. Jenis node berikut mengembalikan nilai yang tercantum. Semua jenis node lainnya mengembalikan string kosong.

| Tipe Node | Nama |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nama atribut. |
| DocumentType| Nama tipe dokumen. |
| Element| Nama tag. |
| EntityReference| Nama entitas yang direferensikan. |
| ProcessingInstruction| Target dari instruksi pemrosesan. |
| [XmlDeclaration](../../xmldeclaration/)| String literal `xml`. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNodeReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)