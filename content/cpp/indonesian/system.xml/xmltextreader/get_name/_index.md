---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama yang memenuhi syarat dari node saat ini.
type: docs
weight: 14
url: /id/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() metode


Mengembalikan nama yang memenuhi syarat dari node saat ini.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Nilai Kembalian

Nama yang memenuhi syarat dari node saat ini. Misalnya, **Name** adalah **bk:book** untuk elemen **<bk:book>**.
## Catatan



Nama yang dikembalikan bergantung pada nilai [XmlTextReader::get_NodeType](../get_nodetype/) dari node. Tipe node berikut mengembalikan nilai yang tercantum. Semua tipe node lainnya mengembalikan string kosong. 

| Jenis Node | Nama |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nama atribut. |
| DocumentType| Nama tipe dokumen. |
| Element| Nama tag. |
| EntityReference| Nama entitas yang direferensikan. |
| ProcessingInstruction| Target dari instruksi pemrosesan. |
| [XmlDeclaration](../../xmldeclaration/)| String literal `xml`. |


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlTextReader](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)