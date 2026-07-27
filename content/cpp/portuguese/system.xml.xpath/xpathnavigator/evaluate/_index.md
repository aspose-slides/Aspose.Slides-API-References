---
title: Evaluate()
second_title: Referência da API Aspose.Slides para C++
description: Avalia a expressão XPath especificada e retorna o resultado tipado.
type: docs
weight: 807
url: /pt/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) método

Avalia a expressão [XPath](../../) especificada e retorna o resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Uma string que representa uma expressão [XPath](../../) que pode ser avaliada. |

### Valor de retorno

O resultado da expressão ([Boolean](../../../system/boolean/), número, string ou conjunto de nós). Isso mapeia para os objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) método

Avalia a expressão [XPath](../../) especificada e retorna o resultado tipado, usando o objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver prefixos de namespace na expressão [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Uma string que representa uma expressão [XPath](../../) que pode ser avaliada. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | O objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefixos de namespace na expressão [XPath](../../). |

### Valor de retorno

O resultado da expressão ([Boolean](../../../system/boolean/), número, string ou conjunto de nós). Isso mapeia para os objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) método

Avalia o [XPathExpression](../../xpathexpression/) e retorna o resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Um [XPathExpression](../../xpathexpression/) que pode ser avaliado. |

### Valor de retorno

O resultado da expressão ([Boolean](../../../system/boolean/), número, string ou conjunto de nós). Isso mapeia para os objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) método

Usa o contexto fornecido para avaliar o [XPathExpression](../../xpathexpression/) e retorna o resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Um [XPathExpression](../../xpathexpression/) que pode ser avaliado. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Um [XPathNodeIterator](../../xpathnodeiterator/) que aponta para o conjunto de nós selecionado onde a avaliação deve ser executada. |

### Valor de retorno

O resultado da expressão ([Boolean](../../../system/boolean/), número, string ou conjunto de nós). Isso mapeia para os objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) ou [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Classe [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Classe [XPathExpression](../../xpathexpression/)
* Classe [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)