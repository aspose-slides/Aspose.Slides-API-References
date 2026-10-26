---
title: CreateNode()
second_title: Aspose.Slides pro C++ – reference API
description: "Vytvoří XmlNode se zadaným XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name a XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /cs/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String&, const String&, const String&) method

Vytvoří [XmlNode](../../xmlnode/) se zadaným XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType nového uzlu. |
| prefix | const [String](../../../system/string/)\& | Předpona nového uzlu. |
| name | const [String](../../../system/string/)\& | Místní název nového uzlu. |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru nového uzlu. |

### Návratová hodnota

Nový [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String&, const String&, const String&) method

Vytvoří [XmlNode](../../xmlnode/) se zadaným typem uzlu, [XmlDocument::get_Name](../get_name/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) verze XmlNodeType nového uzlu. Tento parametr musí být jednou z hodnot uvedených v následující tabulce. |
| name | const [String](../../../system/string/)\& | Kvalifikovaný název nového uzlu. Pokud název obsahuje dvojtečku, je rozdělen na komponenty [XmlNode::get_Prefix](../../xmlnode/get_prefix/) a [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru nového uzlu. |

### Návratová hodnota

Nový [XmlNode](../../xmlnode/).

## Poznámky

Parametr **nodeTypeString** rozlišuje velká a malá písmena a musí být jednou z hodnot v následující tabulce: 

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

## XmlDocument::CreateNode(XmlNodeType, const String&, const String&) method

Vytvoří [XmlNode](../../xmlnode/) se zadaným XmlNodeType, [XmlDocument::get_Name](../get_name/) a [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType nového uzlu. |
| name | const [String](../../../system/string/)\& | Kvalifikovaný název nového uzlu. Pokud název obsahuje dvojtečku, je rozdělen na komponenty [XmlNode::get_Prefix](../../xmlnode/get_prefix/) a [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI jmenného prostoru nového uzlu. |

### Návratová hodnota

Nový [XmlNode](../../xmlnode/).

## Viz také

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)