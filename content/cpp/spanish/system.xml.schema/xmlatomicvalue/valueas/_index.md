---
title: ValueAs()
second_title: Aspose.Slides for C++ Referencia de API
description: Devuelve el valor del elemento o atributo XML validado como el tipo especificado usando el objeto IXmlNamespaceResolver especificado para resolver los prefijos de espacio de nombres.
type: docs
weight: 144
url: /es/system.xml.schema/xmlatomicvalue/valueas/
---
## XmlAtomicValue::ValueAs(const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method


Devuelve el valor del elemento o atributo XML validado como el tipo especificado usando el objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) especificado para resolver los prefijos de espacio de nombres.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlAtomicValue::ValueAs(const TypeInfo &type, SharedPtr<IXmlNamespaceResolver> nsResolver) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| type | const [TypeInfo](../../../system/typeinfo/)\& | El tipo en el que se debe devolver el valor del elemento o atributo XML validado. |
| nsResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | El objeto [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver los prefijos de espacio de nombres. |

### Valor de retorno

El valor del elemento o atributo XML validado como el tipo solicitado.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Clase [XmlAtomicValue](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)