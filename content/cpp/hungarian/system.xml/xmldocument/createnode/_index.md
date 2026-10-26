---
title: CreateNode()
second_title: Aspose.Slides C++ API Referenciája
description: "Létrehoz egy XmlNode-ot a megadott XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name és XmlNode::get_NamespaceURI használatával."
type: docs
weight: 482
url: /hu/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method

Létrehoz egy [XmlNode](../../xmlnode/)-t a megadott XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Az új csomópont XmlNodeType-ja. |
| prefix | const [String](../../../system/string/)\& | Az új csomópont előtagja. |
| name | const [String](../../../system/string/)\& | Az új csomópont helyi neve. |
| namespaceURI | const [String](../../../system/string/)\& | Az új csomópont névtér-URI-ja. |

### Visszatérési érték

Az új [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method

Létrehoz egy [XmlNode](../../xmlnode/)-t a megadott csomópont típussal, [XmlDocument::get_Name](../get_name/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) változata az új csomópont XmlNodeType-jának. Ennek a paraméternek a táblázatban felsorolt értékek egyike kell legyen. |
| name | const [String](../../../system/string/)\& | Az új csomópont minősített neve. Ha a név kettőspontot tartalmaz, akkor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) és [XmlDocument::get_LocalName](../get_localname/) részekre lesz bontva. |
| namespaceURI | const [String](../../../system/string/)\& | Az új csomópont névtér-URI-ja. |

### Visszatérési érték

Az új [XmlNode](../../xmlnode/).

## Megjegyzés

A **nodeTypeString** paraméter kis- és nagybetű érzékeny, és a következő táblázatban szereplő értékek egyike kell legyen:

| nodeTypeString | XmlNodeType |
| --- | --- |
| attribute| [Attribute](../../../system/attribute/)|
| cdatasection| CDATA |
| comment| Comment |
| document| Document |
| documentfragment| DocumentFragment |
| documenttype| DocumentType |
| element| Element |
| entityreference| EntityReference |
| processinginstruction| ProcessingInstruction |
| significantwhitespace| SignificantWhitespace |
| text| [Text](../../../system.text/)|
| whitespace| Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method

Létrehoz egy [XmlNode](../../xmlnode/)-t a megadott XmlNodeType, [XmlDocument::get_Name](../get_name/) és [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) értékekkel.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Az új csomópont XmlNodeType-ja. |
| name | const [String](../../../system/string/)\& | Az új csomópont minősített neve. Ha a név kettőspontot tartalmaz, akkor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) és [XmlDocument::get_LocalName](../get_localname/) részekre lesz bontva. |
| namespaceURI | const [String](../../../system/string/)\& | Az új csomópont névtér-URI-ja. |

### Visszatérési érték

Az új [XmlNode](../../xmlnode/).

## Lásd még

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlNode](../../xmlnode/)
* Osztály [String](../../../system/string/)
* Osztály [XmlDocument](../)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)