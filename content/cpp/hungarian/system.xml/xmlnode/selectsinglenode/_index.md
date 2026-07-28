---
title: SelectSingleNode()
second_title: Aspose.Slides C++ API hivatkozás
description: Kiválasztja az első XmlNode elemet, amely megfelel az XPath kifejezésnek.
type: docs
weight: 352
url: /hu/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) metódus


Kiválasztja az első [XmlNode](../) elemet, amely megfelel a [XPath](../../../system.xml.xpath/) kifejezésnek.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A [XPath](../../../system.xml.xpath/) kifejezés. |

### Visszatérési érték

Az első [XmlNode](../) amely megfelel a [XPath](../../../system.xml.xpath/) lekérdezésnek, vagy **nullptr**, ha nem található megfelelő csomópont.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metódus


Kiválasztja az első [XmlNode](../) elemet, amely megfelel a [XPath](../../../system.xml.xpath/) kifejezésnek. A [XPath](../../../system.xml.xpath/) kifejezésben található összes előtag a megadott [XmlNamespaceManager](../../xmlnamespacemanager/) segítségével kerül feloldásra.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A [XPath](../../../system.xml.xpath/) kifejezés. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Egy [XmlNamespaceManager](../../xmlnamespacemanager/) a [XPath](../../../system.xml.xpath/) kifejezés előtagjaiban szereplő névterek feloldásához. |

### Visszatérési érték

Az első [XmlNode](../) amely megfelel a [XPath](../../../system.xml.xpath/) lekérdezésnek, vagy **nullptr**, ha nem található megfelelő csomópont.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../)
* Osztály [String](../../../system/string/)
* Osztály [XmlNamespaceManager](../../xmlnamespacemanager/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)