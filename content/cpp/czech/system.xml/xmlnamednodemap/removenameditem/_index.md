---
title: RemoveNamedItem()
second_title: Aspose.Slides pro C++ API Reference
description: Odstraňuje uzel z XmlNamedNodeMap.
type: docs
weight: 40
url: /cs/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metoda

Odstraňuje uzel z [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| name | [String](../../../system/string/) | Kvalifikovaný název uzlu, který se má odstranit. Název se porovnává s hodnotou [XmlNode::get_Name](../../xmlnode/get_name/) odpovídajícího uzlu. |

### Návratová hodnota

[XmlNode](../../xmlnode/) odstraněný z tohoto [XmlNamedNodeMap](../) nebo **nullptr**, pokud nebyl nalezen odpovídající uzel.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metoda

Odstraňuje uzel s odpovídajícími hodnotami [XmlNode::get_LocalName](../../xmlnode/get_localname/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Lokální název uzlu, který se má odstranit. |
| namespaceURI | [String](../../../system/string/) | URI jmenného prostoru uzlu, který se má odstranit. |

### Návratová hodnota

[XmlNode](../../xmlnode/) odstraněný nebo **nullptr**, pokud nebyl nalezen odpovídající uzel.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [XmlNode](../../xmlnode/)
* Třída [String](../../../system/string/)
* Třída [XmlNamedNodeMap](../)
* Jmenný prostor [System::Xml](../../)
* Library [Aspose.Slides](../../../)