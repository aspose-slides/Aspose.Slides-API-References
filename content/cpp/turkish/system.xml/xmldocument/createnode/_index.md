---
title: CreateNode()
second_title: Aspose.Slides for C++ API Referansı
description: "Belirtilen XmlNodeType, XmlNode::get_Prefix, XmlDocument::get_Name ve XmlNode::get_NamespaceURI ile bir XmlNode oluşturur."
type: docs
weight: 482
url: /tr/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method

Belirtilen XmlNodeType, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Yeni düğümün XmlNodeType'ı. |
| prefix | const [String](../../../system/string/)\& | Yeni düğümün ön eki. |
| name | const [String](../../../system/string/)\& | Yeni düğümün yerel adı. |
| namespaceURI | const [String](../../../system/string/)\& | Yeni düğümün ad alanı URI'si. |

### Return Value

Yeni [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method

Belirtilen düğüm türü, [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) sürümü yeni düğümün XmlNodeType'ı. Bu parametre aşağıdaki tabloda listelenen değerlerden biri olmalıdır. |
| name | const [String](../../../system/string/)\& | Yeni düğümün nitelikli adı. Ad bir iki nokta üst üste (:) içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ve [XmlDocument::get_LocalName](../get_localname/) bileşenlerine ayrılır. |
| namespaceURI | const [String](../../../system/string/)\& | Yeni düğümün ad alanı URI'si. |

### Return Value

Yeni [XmlNode](../../xmlnode/).

## Remarks

**nodeTypeString** parametresi büyük/küçük harfe duyarlıdır ve aşağıdaki tabloda listelenen değerlerden biri olmalıdır:

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

Belirtilen XmlNodeType, [XmlDocument::get_Name](../get_name/) ve [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) ile bir [XmlNode](../../xmlnode/) oluşturur.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | Yeni düğümün XmlNodeType'ı. |
| name | const [String](../../../system/string/)\& | Yeni düğümün nitelikli adı. Ad bir iki nokta üst üste (:) içeriyorsa, [XmlNode::get_Prefix](../../xmlnode/get_prefix/) ve [XmlDocument::get_LocalName](../get_localname/) bileşenlerine ayrılır. |
| namespaceURI | const [String](../../../system/string/)\& | Yeni düğümün ad alanı URI'si. |

### Return Value

Yeni [XmlNode](../../xmlnode/).

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)