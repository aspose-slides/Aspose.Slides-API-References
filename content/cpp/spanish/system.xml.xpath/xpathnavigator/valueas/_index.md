---
title: ValueAs()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto IXmlNamespaceResolver especificado para resolver los prefijos de espacio de nombres.
type: docs
weight: 378
url: /es/system.xml.xpath/xpathnavigator/valueas/
---
## XPathNavigator::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método

Devuelve el valor del nodo actual como el Tipo especificado, usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::XPath::XPathNavigator::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El Tipo al que se devolverá el valor del nodo actual. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los prefijos de espacio de nombres. |

### Valor devuelto

El valor del nodo actual como el Tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Clase [XPathNavigator](../)
* Espacio de nombres [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)