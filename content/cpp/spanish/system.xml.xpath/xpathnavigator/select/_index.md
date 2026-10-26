---
title: Select()
second_title: Referencia de la API de Aspose.Slides para C++
description: Selecciona un conjunto de nodos, usando la expresión XPath especificada.
type: docs
weight: 794
url: /es/system.xml.xpath/xpathnavigator/select/
---
## XPathNavigator::Select(String) método

Selecciona un conjunto de nodos, usando la expresión [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) que representa una expresión [XPath](../../). |

### Valor de retorno

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## XPathNavigator::Select(String, SharedPtr\<IXmlNamespaceResolver\>) método

Selecciona un conjunto de nodos usando la expresión [XPath](../../) especificada con el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) que representa una expresión [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilizado para resolver los prefijos de espacio de nombres. |

### Valor de retorno

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## XPathNavigator::Select(SharedPtr\<XPathExpression\>) método

Selecciona un conjunto de nodos usando el [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual SharedPtr<XPathNodeIterator> System::Xml::XPath::XPathNavigator::Select(SharedPtr<XPathExpression> expr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expr | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un objeto [XPathExpression](../../xpathexpression/) que contiene la consulta [XPath](../../) compilada. |

### Valor de retorno

Un [XPathNodeIterator](../../xpathnodeiterator/) que apunta al conjunto de nodos seleccionado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XPathNodeIterator](../../xpathnodeiterator/)
* Clase [String](../../../system/string/)
* Clase [XPathNavigator](../)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Clase [XPathExpression](../../xpathexpression/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)