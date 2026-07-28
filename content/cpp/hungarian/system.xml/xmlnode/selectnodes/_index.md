---
title: SelectNodes()
second_title: Aspose.Slides for C++ API referenciája
description: Kiválaszt egy csomópontlistát, amely megfelel az XPath kifejezésnek.
type: docs
weight: 365
url: /hu/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) metódus

Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../../system.xml.xpath/) kifejezésnek.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A [XPath](../../../system.xml.xpath/) kifejezés. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/), amely a [XPath](../../../system.xml.xpath/) lekérdezésnek megfelelő csomópontok gyűjteményét tartalmazza.

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) metódus

Kiválaszt egy csomópontlistát, amely megfelel a [XPath](../../../system.xml.xpath/) kifejezésnek. A [XPath](../../../system.xml.xpath/) kifejezésben található előtagok a megadott [XmlNamespaceManager](../../xmlnamespacemanager/) segítségével kerülnek feloldásra.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A [XPath](../../../system.xml.xpath/) kifejezés. |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Egy [XmlNamespaceManager](../../xmlnamespacemanager/), amelyet a [XPath](../../../system.xml.xpath/) kifejezésben előforduló előtagok névtérfeloldásához használnak. |

### Visszatérési érték

Egy [XmlNodeList](../../xmlnodelist/), amely a [XPath](../../../system.xml.xpath/) lekérdezésnek megfelelő csomópontok gyűjteményét tartalmazza.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNodeList](../../xmlnodelist/)
* Osztály [String](../../../system/string/)
* Osztály [XmlNode](../)
* Osztály [XmlNamespaceManager](../../xmlnamespacemanager/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)