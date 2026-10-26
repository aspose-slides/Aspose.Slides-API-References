---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama yang berkualifikasi dari node, ketika ditimpa dalam kelas turunan.
type: docs
weight: 1
url: /id/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() metode


Mengembalikan nama yang berkualifikasi dari node, ketika ditimpa dalam kelas turunan.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```


### Nilai Kembali

Nama yang berkualifikasi dari node.
## Catatan



Nama yang dikembalikan bergantung pada [XmlNode::get_NodeType](../get_nodetype/) node: 

| Tipe | Nama |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nama yang berkualifikasi dari atribut. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Nama tipe dokumen. |
| Element | Nama yang berkualifikasi dari elemen. |
| Entity | Nama entitas. |
| EntityReference | Nama entitas yang dirujuk. |
| Notation | Nama notasi. |
| ProcessingInstruction | Target instruksi pemrosesan. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNode](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)