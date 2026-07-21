---
title: CreateNode()
second_title: Aspose.Slides для C++ справки API
description: "Создает XmlNode с указанными XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name и XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /ru/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) метод

Создает [XmlNode](../../xmlnode/) с указанным XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType нового узла. |
| prefix | const [String](../../../system/string/)\& | Префикс нового узла. |
| name | const [String](../../../system/string/)\& | Локальное имя нового узла. |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имен нового узла. |

### Возвращаемое значение

Новый [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) метод

Создает [XmlNode](../../xmlnode/) с указанным типом узла, [XmlDocument::get_Name](../get_name/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) версия XmlNodeType нового узла. Этот параметр должен быть одним из значений, перечисленных в таблице ниже. |
| name | const [String](../../../system/string/)\& | Полное имя нового узла. Если имя содержит двоеточие, оно разбивается на компоненты [XmlNode::get_Prefix](../../xmlnode/get_prefix/) и [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имен нового узла. |

### Возвращаемое значение

Новый [XmlNode](../../xmlnode/).

## Примечания

Параметр **nodeTypeString** чувствителен к регистру и должен быть одним из значений в следующей таблице:

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

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) метод

Создает [XmlNode](../../xmlnode/) с указанным XmlNodeType, [XmlDocument::get_Name](../get_name/) и [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | XmlNodeType нового узла. |
| name | const [String](../../../system/string/)\& | Полное имя нового узла. Если имя содержит двоеточие, оно разбивается на компоненты [XmlNode::get_Prefix](../../xmlnode/get_prefix/) и [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | URI пространства имен нового узла. |

### Возвращаемое значение

Новый [XmlNode](../../xmlnode/).

## См. также

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)