---
title: RemoveNamedItem()
second_title: Aspose.Slides C++ API referenciája
description: Eltávolítja a csomópontot az XmlNamedNodeMap-ból.
type: docs
weight: 40
url: /hu/system.xml/xmlnamednodemap/removenameditem/
---
## XmlNamedNodeMap::RemoveNamedItem(String) metódus


Eltávolítja a csomópontot a [XmlNamedNodeMap](../)-ból.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A törlendő csomópont minősített neve. A név a [XmlNode::get_Name](../../xmlnode/get_name/) értékével egyezik a megfelelő csomópont esetén. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) eltávolítva ebből a [XmlNamedNodeMap](../)-ból, vagy **nullptr**, ha nem található egyező csomópont.

## XmlNamedNodeMap::RemoveNamedItem(String, String) metódus


Eltávolít egy csomópontot a megfelelő [XmlNode::get_LocalName](../../xmlnode/get_localname/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::RemoveNamedItem(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A törlendő csomópont helyi neve. |
| namespaceURI | [String](../../../system/string/) | A törlendő csomópont névterének URI-ja. |

### Visszatérési érték

A [XmlNode](../../xmlnode/) eltávolítva, vagy **nullptr**, ha nem található egyező csomópont.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)