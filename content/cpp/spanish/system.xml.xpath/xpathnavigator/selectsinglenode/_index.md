---
title: SelectSingleNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Selecciona un nodo único en el XPathNavigator usando la consulta XPath especificada.
type: docs
weight: 781
url: /es/system.xml.xpath/xpathnavigator/selectsinglenode/
---
## XPathNavigator::SelectSingleNode(String) método


Selecciona un nodo único en el [XPathNavigator](../) usando la consulta [XPath](../../) especificada.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) que representa una expresión [XPath](../../). |

### Valor devuelto

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario, **nullptr** si no hay resultados de la consulta.

## XPathNavigator::SelectSingleNode(String, SharedPtr\<IXmlNamespaceResolver\>) método


Selecciona un nodo único en el objeto [XPathNavigator](../) usando la consulta [XPath](../../) especificada con el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(String xpath, SharedPtr<IXmlNamespaceResolver> resolver)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | [String](../../../system/string/) | Un [String](../../../system/string/) que representa una expresión [XPath](../../). |
| resolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los prefijos de espacio de nombres en la consulta [XPath](../../). |

### Valor devuelto

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario **nullptr** si no hay resultados de la consulta.

## XPathNavigator::SelectSingleNode(SharedPtr\<XPathExpression\>) método


Selecciona un nodo único en el [XPathNavigator](../) usando el objeto [XPathExpression](../../xpathexpression/) especificado.

```cpp
virtual SharedPtr<XPathNavigator> System::Xml::XPath::XPathNavigator::SelectSingleNode(SharedPtr<XPathExpression> expression)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| expression | [SharedPtr](../../../system/sharedptr/)\<[XPathExpression](../../xpathexpression/)\> | Un objeto [XPathExpression](../../xpathexpression/) que contiene la consulta [XPath](../../) compilada. |

### Valor devuelto

Un objeto [XPathNavigator](../) que contiene el primer nodo coincidente para la consulta [XPath](../../) especificada; de lo contrario **nullptr** si no hay resultados de la consulta.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Class [XPathExpression](../../xpathexpression/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)