---
title: Select()
second_title: Referência da API Aspose.Slides para C++
description: Seleciona um conjunto de nós, usando a expressão XPath especificada.
type: docs
weight: 794
url: /pt/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) método

Seleciona um conjunto de nós usando a expressão [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Um [String](../../../system/string/) que representa uma expressão [XPath](../../). |

### Valor de Retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que aponta para o conjunto de nós selecionado.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) método

Seleciona um conjunto de nós usando a expressão [XPath](../../) especificada com o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Um [String](../../../system/string/) que representa uma expressão [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace. |

### Valor de Retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que aponta para o conjunto de nós selecionado.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) método

Seleciona um conjunto de nós usando o [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Um objeto [XPathExpression](../../xpathexpression/) contendo a consulta [XPath](../../) compilada. |

### Valor de Retorno

Um [XPathNodeIterator](../../xpathnodeiterator/) que aponta para o conjunto de nós selecionado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)