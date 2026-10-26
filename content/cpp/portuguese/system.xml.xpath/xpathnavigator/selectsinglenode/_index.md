---
title: SelectSingleNode()
second_title: Referência da API Aspose.Slides para C++
description: Seleciona um único nó no XPathNavigator usando a consulta XPath especificada.
type: docs
weight: 781
url: /pt/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) método


Seleciona um único nó no [XPathNavigator](../) usando a consulta [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Um [String](../../../system/string/) que representa uma expressão [XPath](../../). |

### Valor de Retorno

Um objeto [XPathNavigator](../) que contém o primeiro nó correspondente à consulta [XPath](../../) especificada; caso contrário, **nullptr** se não houver resultados da consulta.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) método


Seleciona um único nó no objeto [XPathNavigator](../) usando a consulta [XPath](../../) especificada com o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Um [String](../../../system/string/) que representa uma expressão [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace na consulta [XPath](../../). |

### Valor de Retorno

Um objeto [XPathNavigator](../) que contém o primeiro nó correspondente à consulta [XPath](../../) especificada; caso contrário, **nullptr** se não houver resultados da consulta.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) método


Seleciona um único nó no [XPathNavigator](../) usando o objeto [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Um objeto [XPathExpression](../../xpathexpression/) contendo a consulta [XPath](../../) compilada. |

### Valor de Retorno

Um objeto [XPathNavigator](../) que contém o primeiro nó correspondente à consulta [XPath](../../) especificada; caso contrário, **nullptr** se não houver resultados da consulta.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)