---
title: CreateNode()
second_title: Referensi API Aspose.Slides untuk C++
description: "Membuat sebuah XmlNode dengan XmlNodeType yang ditentukan, XmlNode::get_Prefix, XmlDocument::get_Name, dan XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /id/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) metode

Membuat sebuah [XmlNode](../../xmlnode/) dengan XmlNodeType yang ditentukan, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/), dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari node baru. |
| prefix | const [String](../../../system/string/)\& | Prefiks dari node baru. |
| name | const [String](../../../system/string/)\& | Nama lokal dari node baru. |
| namespaceURI | const [String](../../../system/string/)\& | URI namespace dari node baru. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) baru.

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) metode

Membuat sebuah [XmlNode](../../xmlnode/) dengan tipe node yang ditentukan, [XmlDocument::get_Name](../get_name/), dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) versi dari XmlNodeType node baru. Parameter ini harus salah satu nilai yang tercantum dalam tabel di bawah. |
| name | const [String](../../../system/string/)\& | Nama terkwalifikasi dari node baru. Jika nama mengandung titik dua, maka diurai menjadi komponen [XmlNode::get_Prefix](../../xmlnode/get_prefix/) dan [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI namespace dari node baru. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) baru.

## Catatan

Parameter **nodeTypeString** bersifat case sensitive dan harus salah satu nilai dalam tabel berikut:

| nodeTypeString| XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) metode

Membuat sebuah [XmlNode](../../xmlnode/) dengan XmlNodeType yang ditentukan, [XmlDocument::get_Name](../get_name/), dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType dari node baru. |
| name | const [String](../../../system/string/)\& | Nama terkwalifikasi dari node baru. Jika nama mengandung titik dua, maka diurai menjadi komponen [XmlNode::get_Prefix](../../xmlnode/get_prefix/) dan [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI namespace dari node baru. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) baru.

## Lihat Juga

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)