---
title: CreateNode()
second_title: Aspose.Slides per C++ Riferimento API
description: "Crea un XmlNode con lo XmlNodeType specificato, XmlNode::get_Prefix, XmlDocument::get_Name e XmlNode::get_NamespaceURI."
type: docs
weight: 482
url: /it/system.xml/xmldocument/createnode/
---
## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&, const String\&) metodo

Crea un [XmlNode](../../xmlnode/) con il XmlNodeType specificato, [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &prefix, const String &name, const String &namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | L'XmlNodeType del nuovo nodo. |
| prefix | const [String](../../../system/string/)\& | Il prefisso del nuovo nodo. |
| name | const [String](../../../system/string/)\& | Il nome locale del nuovo nodo. |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi del nuovo nodo. |

### Valore di ritorno

Il nuovo [XmlNode](../../xmlnode/).

## XmlDocument::CreateNode(const String\&, const String\&, const String\&) metodo

Crea un [XmlNode](../../xmlnode/) con il tipo di nodo specificato, [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(const String &nodeTypeString, const String &name, const String &namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nodeTypeString | const [String](../../../system/string/)\& | [String](../../../system/string/) versione dell'XmlNodeType del nuovo nodo. Questo parametro deve essere uno dei valori elencati nella tabella sottostante. |
| name | const [String](../../../system/string/)\& | Il nome qualificato del nuovo nodo. Se il nome contiene due punti, viene analizzato in componenti [XmlNode::get_Prefix](../../xmlnode/get_prefix/) e [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi del nuovo nodo. |

### Valore di ritorno

Il nuovo [XmlNode](../../xmlnode/).

## Osservazioni

Il parametro **nodeTypeString** è sensibile al maiuscolo/minuscolo e deve essere uno dei valori nella tabella seguente:

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

## XmlDocument::CreateNode(XmlNodeType, const String\&, const String\&) metodo

Crea un [XmlNode](../../xmlnode/) con il XmlNodeType specificato, [XmlDocument::get_Name](../get_name/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlDocument::CreateNode(XmlNodeType type, const String &name, const String &namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | [XmlNodeType](../../xmlnodetype/) | L'XmlNodeType del nuovo nodo. |
| name | const [String](../../../system/string/)\& | Il nome qualificato del nuovo nodo. Se il nome contiene due punti, viene analizzato in componenti [XmlNode::get_Prefix](../../xmlnode/get_prefix/) e [XmlDocument::get_LocalName](../get_localname/). |
| namespaceURI | const [String](../../../system/string/)\& | L'URI dello spazio dei nomi del nuovo nodo. |

### Valore di ritorno

Il nuovo [XmlNode](../../xmlnode/).

## Vedi anche

* Enum [XmlNodeType](../../xmlnodetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../../xmlnode/)
* Classe [String](../../../system/string/)
* Classe [XmlDocument](../)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)