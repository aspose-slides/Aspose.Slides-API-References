---
title: Matches()
second_title: Referencia de API de Aspose.Slides para C++
description: Determina si el nodo actual coincide con la XPathExpression especificada.
type: docs
weight: 820
url: /es/system.xml.xpath/xpathnavigator/matches/
---
## XPathNavigator::Matches(SharedPtr\<XPathExpression\>) método


Determina si el nodo actual coincide con el [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(SharedPtr<XPathExpression> expr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un objeto [XPathExpression](../../xpathexpression/) que contiene la expresión [XPath](../../) compilada. |

### Valor devuelto

**true** si el nodo actual coincide con el [XPathExpression](../../xpathexpression/); de lo contrario, **false**.

## XPathNavigator::Matches(String) método


Determina si el nodo actual coincide con la expresión [XPath](../../) especificada.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::Matches(String xpath)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | La expresión [XPath](../../). |

### Valor devuelto

**true** si el nodo actual coincide con la expresión [XPath](../../) especificada; de lo contrario, **false**.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathExpression](../../xpathexpression/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)