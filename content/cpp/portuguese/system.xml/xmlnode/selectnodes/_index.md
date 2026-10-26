---
title: SelectNodes()
second_title: Referência da API Aspose.Slides para C++
description: Seleciona uma lista de nós que correspondem à expressão XPath.
type: docs
weight: 365
url: /pt/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) método


Seleciona uma lista de nós correspondentes à expressão [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A expressão [XPath](../../../system.xml.xpath/). |

### Valor de retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma coleção de nós correspondentes à consulta [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) método


Seleciona uma lista de nós correspondentes à expressão [XPath](../../../system.xml.xpath/). Quaisquer prefixos encontrados na expressão [XPath](../../../system.xml.xpath/) são resolvidos usando o [XmlNamespaceManager](../../xmlnamespacemanager/) fornecido.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A expressão [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Um [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para resolver namespaces para prefixos na expressão [XPath](../../../system.xml.xpath/). |

### Valor de retorno

Um [XmlNodeList](../../xmlnodelist/) contendo uma coleção de nós correspondentes à consulta [XPath](../../../system.xml.xpath/).

## Veja também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNodeList](../../xmlnodelist/)
* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)