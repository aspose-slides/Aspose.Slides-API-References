---
title: get_Value()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai node.
type: docs
weight: 14
url: /id/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() metode

Mengembalikan nilai node.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Nilai Kembali

Nilai yang dikembalikan tergantung pada [XmlNode::get_NodeType](../get_nodetype/) node:

| Tipe | Nilai |
| --- | --- |
| [Attribute](../../../system/attribute/)| Nilai atribut. |
| CDATASection | Isi CDATA Section. |
| Comment | Isi komentar. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Anda dapat menggunakan XmlElement::InnerText atau nilai [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) untuk mengakses nilai node elemen. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Seluruh konten kecuali target. |
| [Text](../../../system.text/)| Isi node teks. |
| SignificantWhitespace | Karakter spasi putih. Spasi dapat terdiri dari satu atau lebih karakter spasi, carriage return, line feed, atau tab. |
| Whitespace | Karakter spasi putih. Spasi dapat terdiri dari satu atau lebih karakter spasi, carriage return, line feed, atau tab. |
| [XmlDeclaration](../../xmldeclaration/)| Isi deklarasi (yaitu, semua di antara `<?xml and ?>`). |

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [XmlNode](../)
* Namespace [System::Xml](../../)
* Perpustakaan [Aspose.Slides](../../../)