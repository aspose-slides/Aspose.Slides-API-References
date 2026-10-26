---
title: ChangeType()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por XmlSchemaDatatype, al tipo de tiempo de ejecución especificado.
type: docs
weight: 66
url: /es/system.xml.schema/xmlschemadatatype/changetype/
---
## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&) method

Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por [XmlSchemaDatatype](../), al tipo de tiempo de ejecución especificado.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El valor de entrada a convertir al tipo especificado. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de destino al que se convertirá el valor de entrada. |

### Valor devuelto

El valor de entrada convertido.

## XmlSchemaDatatype::ChangeType(SharedPtr\<Object\>, const TypeInfo\&, SharedPtr\<IXmlNamespaceResolver\>) method

Convierte el valor especificado, cuyo tipo es una de las representaciones válidas del tipo de esquema XML representado por [XmlSchemaDatatype](../), al tipo de tiempo de ejecución especificado usando [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) si [XmlSchemaDatatype](../) representa el tipo **xs:QName** o un tipo derivado del mismo.

```cpp
virtual SharedPtr<Object> System::Xml::Schema::XmlSchemaDatatype::ChangeType(SharedPtr<Object> value, const TypeInfo &targetType, SharedPtr<IXmlNamespaceResolver> namespaceResolver)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | El valor de entrada a convertir al tipo especificado. |
| targetType | const [TypeInfo](../../../system/typeinfo/)\& | El tipo de destino al que se convertirá el valor de entrada. |
| namespaceResolver | [SharedPtr](../../../system/sharedptr/)\<[IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)\> | Un [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/) usado para resolver prefijos de espacio de nombres. Esto solo es útil si [XmlSchemaDatatype](../) representa el tipo **xs:QName** o un tipo derivado del mismo. |

### Valor devuelto

El valor de entrada convertido.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [TypeInfo](../../../system/typeinfo/)
* Clase [XmlSchemaDatatype](../)
* Clase [IXmlNamespaceResolver](../../../system.xml/ixmlnamespaceresolver/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)