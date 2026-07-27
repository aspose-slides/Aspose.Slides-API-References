---
title: SelectSingleNode()
second_title: Aspose.Slides para C++ Referência da API
description: Seleciona o primeiro XmlNode que corresponde à expressão XPath.
type: docs
weight: 352
url: /pt/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) método


Seleciona o primeiro [XmlNode](../) que corresponde à expressão [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A expressão [XPath](../../../system.xml.xpath/). |

### Valor de Retorno

O primeiro [XmlNode](../) que corresponde à consulta [XPath](../../../system.xml.xpath/) ou **nullptr** se nenhum nó correspondente for encontrado.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) método


Seleciona o primeiro [XmlNode](../) que corresponde à expressão [XPath](../../../system.xml.xpath/). Quaisquer prefixos encontrados na expressão [XPath](../../../system.xml.xpath/) são resolvidos usando o [XmlNamespaceManager](../../xmlnamespacemanager/) fornecido.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | A expressão [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Um [XmlNamespaceManager](../../xmlnamespacemanager/) a ser usado para resolver namespaces para prefixos na expressão [XPath](../../../system.xml.xpath/). |

### Valor de Retorno

O primeiro [XmlNode](../) que corresponde à consulta [XPath](../../../system.xml.xpath/) ou **nullptr** se nenhum nó correspondente for encontrado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../)
* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../../xmlnamespacemanager/)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)