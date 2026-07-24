---
title: CreateNode()
second_title: Aspose.Slides für C++ API-Referenz
description: "Erstellt einen XmlNode mit dem angegebenen XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name und XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /de/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String&, const String&, const String&) Methode


Erstellt ein [XmlNode](../../xmlnode/) mit dem angegebenen XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des neuen Knotens. |
| prefix | const [String](../../../system/string/)\& | Das Prefix des neuen Knotens. |
| name | const [String](../../../system/string/)\& | Der lokale Name des neuen Knotens. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des neuen Knotens. |

### Rückgabewert

Der neue [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String&, const String&, const String&) Methode


Erstellt ein [XmlNode](../../xmlnode/) mit dem angegebenen Knotentyp, [XmlDocument::get_Name](../get_name/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) Version des XmlNodeType des neuen Knotens. Dieser Parameter muss einer der unten aufgeführten Werte sein. |
| name | const [String](../../../system/string/)\& | Der qualifizierte Name des neuen Knotens. Enthält der Name einen Doppelpunkt, wird er in [XmlNode::get_Prefix](../../xmlnode/get_prefix/) und [XmlDocument::get_LocalName](../get_localname/) Komponenten zerlegt. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des neuen Knotens. |

### Rückgabewert

Der neue [XmlNode](../../xmlnode/).

## Bemerkungen



Der **nodeTypeString** Parameter ist case-sensitiv und muss einer der Werte in der folgenden Tabelle sein: 

| nodeTypeString| XmlNodeType |
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


## XmlDocument::CreateNode(XmlNodeType, const String&, const String&) Methode


Erstellt ein [XmlNode](../../xmlnode/) mit dem angegebenen XmlNodeType, [XmlDocument::get_Name](../get_name/) und [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Der XmlNodeType des neuen Knotens. |
| name | const [String](../../../system/string/)\& | Der qualifizierte Name des neuen Knotens. Enthält der Name einen Doppelpunkt, wird er in [XmlNode::get_Prefix](../../xmlnode/get_prefix/) und [XmlDocument::get_LocalName](../get_localname/) Komponenten zerlegt. |
| namespaceURI | const [String](../../../system/string/)\& | Der Namespace-URI des neuen Knotens. |

### Rückgabewert

Der neue [XmlNode](../../xmlnode/).

## Siehe auch

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [XmlNode](../../xmlnode/)
* Klasse [String](../../../system/string/)
* Klasse [XmlDocument](../)
* Namensraum [System::Xml](../../)
* Library [Aspose.Slides](../../../)