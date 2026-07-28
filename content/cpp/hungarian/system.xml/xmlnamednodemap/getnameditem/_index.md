---
title: GetNamedItem()
second_title: Aspose.Slides C++ API hivatkozása
description: Lekér egy név alapján megadott XmlNode-ot.
type: docs
weight: 14
url: /hu/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) metódus


Lekér egy [XmlNode](../../xmlnode/) a név alapján.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| name | [String](../../../system/string/) | A lekérendő csomópont minősített neve. A megfelelő csomópont [XmlNode::get_Name](../../xmlnode/get_name/) értékével egyeztetve. |

### Visszatérési érték

Egy [XmlNode](../../xmlnode/) a megadott névvel, vagy **nullptr**, ha nem található megfelelő csomópont.

## XmlNamedNodeMap::GetNamedItem(String, String) metódus


Lekér egy csomópontot, amelynek [XmlNode::get_LocalName](../../xmlnode/get_localname/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értéke megegyezik.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| localName | [String](../../../system/string/) | A lekérendő csomópont helyi neve. |
| namespaceURI | [String](../../../system/string/) | A lekérendő csomópont névterének egységes erőforrás-azonosítója (URI). |

### Visszatérési érték

Egy [XmlNode](../../xmlnode/) a megfelelő helyi névvel és névtér-URI-vel, vagy **nullptr**, ha nem található megfelelő csomópont.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNamedNodeMap](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)