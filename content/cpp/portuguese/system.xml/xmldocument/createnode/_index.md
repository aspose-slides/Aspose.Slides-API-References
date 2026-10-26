---
title: CreateNode()
second_title: Referência da API Aspose.Slides para C++
description: "Cria um XmlNode com o XmlNodeType especificado, XmlNode::get_Prefix, XmlDocument::get_Name e XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /pt/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) method


Cria um [XmlNode](../../xmlnode/) com o XmlNodeType especificado, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do novo nó. |
| prefix | const [String](../../../system/string/)\& | O prefixo do novo nó. |
| name | const [String](../../../system/string/)\& | O nome local do novo nó. |
| namespaceURI | const [String](../../../system/string/)\& | O namespace URI do novo nó. |

### Return Value

O novo [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) method


Cria um [XmlNode](../../xmlnode/) com o tipo de nó especificado, [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) versão do XmlNodeType do novo nó. Este parâmetro deve ser um dos valores listados na tabela abaixo. |
| name | const [String](../../../system/string/)\& | O nome qualificado do novo nó. Se o nome contiver dois-pontos, ele será analisado nos componentes [XmlNode::get_Prefix](../../xmlnode/get_prefix/) e [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | O namespace URI do novo nó. |

### Return Value

O novo [XmlNode](../../xmlnode/).

## Remarks



O parâmetro **nodeTypeString** diferencia maiúsculas de minúsculas e deve ser um dos valores na tabela a seguir: 

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


Cria um [XmlNode](../../xmlnode/) com o XmlNodeType especificado, [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | O XmlNodeType do novo nó. |
| name | const [String](../../../system/string/)\& | O nome qualificado do novo nó. Se o nome contiver dois-pontos, ele será analisado nos componentes [XmlNode::get_Prefix](../../xmlnode/get_prefix/) e [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | O namespace URI do novo nó. |

### Return Value

O novo [XmlNode](../../xmlnode/).

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlDocument](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)