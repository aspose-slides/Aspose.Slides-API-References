---
title: RemoveAttributeNode()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus XmlAttribute yang ditentukan.
type: docs
weight: 274
url: /id/system.xml/xmlelement/removeattributenode/
---
## XmlElement::RemoveAttributeNode(SharedPtr\<XmlAttribute\>) method


Menghapus [XmlAttribute](../../xmlattribute/) yang ditentukan.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(SharedPtr<XmlAttribute> oldAttr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| oldAttr | [SharedPtr](../../../system/sharedptr/)\<[XmlAttribute](../../xmlattribute/)\> | Node [XmlAttribute](../../xmlattribute/) yang akan dihapus. Jika atribut yang dihapus memiliki nilai default, nilainya akan segera diganti. |

### Return Value

[XmlAttribute](../../xmlattribute/) yang dihapus atau **nullptr** jika **oldAttr** bukan node atribut dari [XmlElement](../).

## XmlElement::RemoveAttributeNode(String, String) method


Menghapus [XmlAttribute](../../xmlattribute/) yang ditentukan oleh nama lokal dan namespace URI. (Jika atribut yang dihapus memiliki nilai default, nilainya akan segera diganti).

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::RemoveAttributeNode(String localName, String namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Nama lokal atribut. |
| namespaceURI | [String](../../../system/string/) | Namespace URI atribut. |

### Return Value

[XmlAttribute](../../xmlattribute/) yang dihapus atau **nullptr** jika [XmlElement](../) tidak memiliki node atribut yang cocok.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [XmlAttribute](../../xmlattribute/)
* Kelas [XmlElement](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Xml](../../)
* Pustaka [Aspose.Slides](../../../)