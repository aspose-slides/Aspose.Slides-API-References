---
title: Evaluate()
second_title: Referencia de API de Aspose.Slides para C++
description: Evalúa la expresión XPath especificada y devuelve el resultado tipado.
type: docs
weight: 807
url: /es/system.xml.xpath/xpathnavigator/evaluate/
---
## XPathNavigator::Evaluate(String) método

Evalúa la expresión [XPath](../../) especificada y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Una cadena que representa una expresión [XPath](../../) que puede evaluarse. |

### Valor de retorno

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con los objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(String, SharedPtr\<IXmlNamespaceResolver\>) método

Evalúa la expresión [XPath](../../) especificada y devuelve el resultado tipado, usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres en la expresión [XPath](../../).

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Una cadena que representa una expresión [XPath](../../) que puede evaluarse. |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los prefijos de espacio de nombres en la expresión [XPath](../../). |

### Valor de retorno

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con los objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>) método

Evalúa el [XPathExpression](../../xpathexpression/) y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) que puede evaluarse. |

### Valor de retorno

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con los objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## XPathNavigator::Evaluate(SharedPtr\<XPathExpression\>, SharedPtr\<XPathNodeIterator\>) método

Utiliza el contexto suministrado para evaluar el [XPathExpression](../../xpathexpression/) y devuelve el resultado tipado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathNavigator::Evaluate(SharedPtr<XPathExpression> expr, SharedPtr<XPathNodeIterator> context)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un [XPathExpression](../../xpathexpression/) que puede evaluarse. |
| context | [SharedPtr](../../../system/sharedptr/)\<[XPathNodeIterator](../../xpathnodeiterator/)\> | Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado sobre el cual se realizará la evaluación. |

### Valor de retorno

El resultado de la expresión ([Boolean](../../../system/boolean/), número, cadena o conjunto de nodos). Esto se corresponde con los objetos [Boolean](../../../system/boolean/), [Double](../../../system/double/), [String](../../../system/string/) o [XPathNodeIterator](../../xpathnodeiterator/) respectivamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [String](../../../system/string/)
* Class [XPathNavigator](../)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNodeIterator](../../xpathnodeiterator/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)