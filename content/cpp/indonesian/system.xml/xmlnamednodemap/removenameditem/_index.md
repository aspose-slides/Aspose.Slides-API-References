---
title: RemoveNamedItem()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus node dari XmlNamedNodeMap.
type: docs
weight: 40
url: /id/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metode

Menghapus node dari [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkualifikasi dari node yang akan dihapus. Nama tersebut dicocokkan dengan nilai [XmlNode::get_Name](../../xmlnode/get_name/) dari node yang cocok. |

### Nilai Kembali

[XmlNode](../../xmlnode/) yang dihapus dari [XmlNamedNodeMap](../) ini atau **nullptr** jika tidak ditemukan node yang cocok.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metode

Menghapus node dengan nilai [XmlNode::get_LocalName](../../xmlnode/get_localname/) dan [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) yang cocok.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal dari node yang akan dihapus. |
| namespaceURI | [String](../../../system/string/) | URI namespace dari node yang akan dihapus. |

### Nilai Kembali

[XmlNode](../../xmlnode/) yang dihapus atau **nullptr** jika tidak ditemukan node yang cocok.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlNode](../../xmlnode/)
* Kelas [String](../../../system/string/)
* Kelas [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)