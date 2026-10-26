---
title: get_Name()
second_title: Referensi API Aspose.Slides untuk C++
description: Saat dioverride dalam kelas turunan, mengambil nama lengkap dari node saat ini.
type: docs
weight: 27
url: /id/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() metode

When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### Nilai Kembali

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.

## Keterangan

The name returned is dependent on the [XmlReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| Tipe Node | Nama |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| The name of the attribute. |
| `DocumentType`| The document type name. |
| `Element`| The tag name. |
| `EntityReference`| The name of the entity referenced. |
| `ProcessingInstruction`| The target of the processing instruction. |
| [XmlDeclaration](../../xmldeclaration/)| The literal string `xml`. |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlReader](../)
* Ruang Nama [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)