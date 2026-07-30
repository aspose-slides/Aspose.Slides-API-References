---
title: GetNamedItem()
second_title: Aspose.Slides pro C++ API Reference
description: Načte XmlNode určený názvem.
type: docs
weight: 14
url: /cs/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metoda

Načte [XmlNode](../../xmlnode/) určený názvem.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název uzlu, který se má načíst. Porovnává se s hodnotou [XmlNode::get_Name](../../xmlnode/get_name/) odpovídajícího uzlu. |

### Návratová hodnota

Objekt [XmlNode](../../xmlnode/) se zadaným názvem nebo **nullptr**, pokud odpovídající uzel není nalezen.

## XmlNamedNodeMap::GetNamedItem(String, String) metoda

Načte uzel s odpovídajícími hodnotami [XmlNode::get_LocalName](../../xmlnode/get_localname/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název uzlu, který se má načíst. |
| namespaceURI | [String](../../../system/string/) | Uniform Resource Identifier (URI) jmenného prostoru uzlu, který se má načíst. |

### Návratová hodnota

Objekt [XmlNode](../../xmlnode/) s odpovídajícím lokálním názvem a URI jmenného prostoru nebo **nullptr**, pokud odpovídající uzel nebyl nalezen.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [String](../../../system/string/)
* Třída [XmlNamedNodeMap](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)