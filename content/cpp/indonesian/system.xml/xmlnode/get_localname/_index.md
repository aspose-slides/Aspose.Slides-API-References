---
title: get_LocalName()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nama lokal node, ketika ditimpa dalam kelas turunan.
type: docs
weight: 209
url: /id/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() metode


Mengembalikan nama lokal node, ketika ditimpa dalam kelas turunan.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Nilai Kembalian

Nama node dengan awalan dihapus. Sebagai contoh, **LocalName** adalah **book** untuk elemen **<bk:book>**.
## Catatan



Nama yang dikembalikan bergantung pada [XmlNode::get_NodeType](../get_nodetype/) node: 

| Tipe | Nama |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nama lokal atribut. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | Nama tipe dokumen. |
| Element | Nama lokal elemen. |
| Entity | Nama entitas. |
| EntityReference | Nama entitas yang dirujuk. |
| Notation | Nama notasi. |
| ProcessingInstruction | Tujuan instruksi pemrosesan. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNode](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)