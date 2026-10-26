---
title: GetNamedItem()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengambil sebuah XmlNode yang ditentukan oleh nama.
type: docs
weight: 14
url: /id/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metode

Mengambil [XmlNode](../../xmlnode/) yang ditentukan oleh nama.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama lengkap node yang akan diambil. Nilai tersebut dicocokkan dengan nilai [XmlNode::get_Name](../../xmlnode/get_name/) dari node yang cocok. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) dengan nama yang ditentukan atau **nullptr** jika node yang cocok tidak ditemukan.

## XmlNamedNodeMap::GetNamedItem(String, String) metode

Mengambil node dengan nilai [XmlNode::get_LocalName](../../xmlnode/get_localname/) dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang cocok.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal node yang akan diambil. |
| namespaceURI | [String](../../../system/string/) | Uniform Resource Identifier (URI) namespace dari node yang akan diambil. |

### Nilai Kembalian

[XmlNode](../../xmlnode/) dengan nama lokal dan namespace URI yang cocok atau **nullptr** jika node yang cocok tidak ditemukan.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNamedNodeMap](../)
* Ruang Nama [System::Xml](../../)
* Library [Aspose.Slides](../../../)