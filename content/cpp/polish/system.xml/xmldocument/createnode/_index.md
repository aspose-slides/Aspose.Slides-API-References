---
title: CreateNode()
second_title: Aspose.Slides dla C++ Referencja API
description: "Tworzy XmlNode z określonym XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name i XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /pl/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method

Tworzy [XmlNode](../../xmlnode/) z określonym XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType nowego węzła. |
| prefix | const [String](../../../system/string/)\& | Prefiks nowego węzła. |
| name | const [String](../../../system/string/)\& | Lokalna nazwa nowego węzła. |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw nowego węzła. |

### Wartość zwracana

Nowy [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method

Tworzy [XmlNode](../../xmlnode/) o określonym typie węzła, [XmlDocument::get_Name](../get_name/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) wersja XmlNodeType nowego węzła. Ten parametr musi być jedną z wartości wymienionych w poniższej tabeli. |
| name | const [String](../../../system/string/)\& | W pełni kwalifikowana nazwa nowego węzła. Jeśli nazwa zawiera dwukropek, jest ona analizowana na komponenty [XmlNode::get_Prefix](../../xmlnode/get_prefix/) i [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw nowego węzła. |

### Wartość zwracana

Nowy [XmlNode](../../xmlnode/).

## Uwagi

Parametr **nodeTypeString** jest rozróżniany pod względem wielkości liter i musi być jedną z wartości w poniższej tabeli: 

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

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) method

Tworzy [XmlNode](../../xmlnode/) z określonym XmlNodeType, [XmlDocument::get_Name](../get_name/) i [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType nowego węzła. |
| name | const [String](../../../system/string/)\& | W pełni kwalifikowana nazwa nowego węzła. Jeśli nazwa zawiera dwukropek, jest ona analizowana na komponenty [XmlNode::get_Prefix](../../xmlnode/get_prefix/) i [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI przestrzeni nazw nowego węzła. |

### Wartość zwracana

Nowy [XmlNode](../../xmlnode/).

## Zobacz także

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [XmlNode](../../xmlnode/)
* Klasa [String](../../../system/string/)
* Klasa [XmlDocument](../)
* Przestrzeń nazw [System::Xml](../../)
* Library [Aspose.Slides](../../../)