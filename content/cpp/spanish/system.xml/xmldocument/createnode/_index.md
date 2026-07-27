---
title: CreateNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Crea un XmlNode con el XmlNodeType especificado, XmlNode::get_Prefix, XmlDocument::get_Name y XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /es/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String&, const String&, const String&) método

Crea un [XmlNode](../../xmlnode/) con el XmlNodeType especificado, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del nuevo nodo. |
| prefix | const [String](../../../system/string/)& | El prefijo del nuevo nodo. |
| name | const [String](../../../system/string/)& | El nombre local del nuevo nodo. |
| namespaceURI | const [String](../../../system/string/)& | El URI del espacio de nombres del nuevo nodo. |

### Valor devuelto

El nuevo [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String&, const String&, const String&) método

Crea un [XmlNode](../../xmlnode/) con el tipo de nodo especificado, [XmlDocument::get_Name](../get_name/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)& | Versión [String](../../../system/string/) del XmlNodeType del nuevo nodo. Este parámetro debe ser uno de los valores listados en la tabla a continuación. |
| name | const [String](../../../system/string/)& | El nombre calificado del nuevo nodo. Si el nombre contiene dos puntos, se analiza en los componentes [XmlNode::get_Prefix](../../xmlnode/get_prefix/) y [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)& | El URI del espacio de nombres del nuevo nodo. |

### Valor devuelto

El nuevo [XmlNode](../../xmlnode/).

## Observaciones

El parámetro **nodeTypeString** distingue entre mayúsculas y minúsculas y debe ser uno de los valores en la tabla siguiente: 

| nodeTypeString | XmlNodeType |
| --- | --- |
| attribute | [Attribute](../../../system/attribute/) |
| cdatasection | CDATA |
| comment | Comment |
| document | Document |
| documentfragment | DocumentFragment |
| documenttype | DocumentType |
| element | Element |
| entityreference | EntityReference |
| processinginstruction | ProcessingInstruction |
| significantwhitespace | SignificantWhitespace |
| text | [Text](../../../system.text/) |
| whitespace | Whitespace |

## XmlDocument::CreateNode(XmlNodeType, const String&, const String&) método

Crea un [XmlNode](../../xmlnode/) con el XmlNodeType especificado, [XmlDocument::get_Name](../get_name/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | El XmlNodeType del nuevo nodo. |
| name | const [String](../../../system/string/)& | El nombre calificado del nuevo nodo. Si el nombre contiene dos puntos, se analiza en los componentes [XmlNode::get_Prefix](../../xmlnode/get_prefix/) y [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)& | El URI del espacio de nombres del nuevo nodo. |

### Valor devuelto

El nuevo [XmlNode](../../xmlnode/).

## Véase también

* Enumeración [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../../xmlnode/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)