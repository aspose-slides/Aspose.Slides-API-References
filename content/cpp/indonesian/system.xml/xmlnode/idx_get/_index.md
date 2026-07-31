---
title: idx_get()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan elemen anak pertama dengan XmlNode::get_Name yang ditentukan."
type: docs
weight: 586
url: /id/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) metode


Mengembalikan elemen anak pertama dengan [XmlNode::get_Name](../get_name/) yang ditentukan.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | [String](../../../system/string/) | Nama terkualifikasi elemen yang akan diambil. |

### Nilai Kembalian

[XmlElement](../../xmlelement/) pertama yang cocok dengan nama yang ditentukan. Mengembalikan **nullptr** jika tidak ada yang cocok.

## XmlNode::idx_get(String, String) metode


Mengembalikan elemen anak pertama dengan nilai [XmlNode::get_LocalName](../get_localname/) dan [XmlNode::get_NamespaceURI](../get_namespaceuri/) yang ditentukan.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| localname | [String](../../../system/string/) | Nama lokal elemen. |
| ns | [String](../../../system/string/) | URI namespace elemen. |

### Nilai Kembalian

[XmlElement](../../xmlelement/) pertama dengan **localname** dan **ns** yang cocok. Mengembalikan **nullptr** jika tidak ada yang cocok.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlElement](../../xmlelement/)
* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)