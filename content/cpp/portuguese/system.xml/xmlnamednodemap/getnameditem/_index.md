---
title: GetNamedItem()
second_title: Referência da API Aspose.Slides para C++
description: Recupera um XmlNode especificado por nome.
type: docs
weight: 14
url: /pt/system.xml/xmlnamednodemap/getnameditem/
---
## XmlNamedNodeMap::GetNamedItem(String) método

Recupera um [XmlNode](../../xmlnode/) especificado por nome.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String name)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | O nome qualificado do nó a ser recuperado. É comparado ao valor [XmlNode::get_Name](../../xmlnode/get_name/) do nó correspondente. |

### Valor de Retorno

Um [XmlNode](../../xmlnode/) com o nome especificado ou **nullptr** se um nó correspondente não for encontrado.

## XmlNamedNodeMap::GetNamedItem(String, String) método

Recupera um nó com os valores [XmlNode::get_LocalName](../../xmlnode/get_localname/) e [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) correspondentes.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::GetNamedItem(String localName, String namespaceURI)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | O nome local do nó a ser recuperado. |
| namespaceURI | [String](../../../system/string/) | O Identificador Uniforme de Recursos (URI) do namespace do nó a ser recuperado. |

### Valor de Retorno

Um [XmlNode](../../xmlnode/) com o nome local e o URI do namespace correspondentes ou **nullptr** se um nó correspondente não for encontrado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [String](../../../system/string/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)