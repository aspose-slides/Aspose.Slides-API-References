---
title: ValueAs()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor del elemento como el tipo especificado.
type: docs
weight: 131
url: /es/system.xml.xpath/xpathitem/valueas/
---
## XPathItem::ValueAs(const TypeInfo\&) método


Devuelve el valor del elemento como el tipo especificado.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo con el que se devuelve el valor del elemento. |

### Valor devuelto

El valor del elemento como el tipo solicitado.

## XPathItem::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) método


Cuando se sobrescribe en una clase derivada, devuelve el valor del elemento como el tipo especificado usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
virtual SharedPtr<Object> System::Xml::XPath::XPathItem::ValueAs(const TypeInfo &returnType, SharedPtr<IXmlNamespaceResolver> nsResolver)=0
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| returnType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo con el que se devuelve el valor del elemento. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) utilizado para resolver los prefijos de espacio de nombres. |

### Valor devuelto

El valor del elemento como el tipo solicitado.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XPathItem](../)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)