---
title: ValidateEndElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Verifica si el contenido de texto del elemento es válido según su tipo de datos para los elementos con contenido simple, y verifica si el contenido del elemento actual está completo para los elementos con contenido complejo.
type: docs
weight: 209
url: /es/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) método


Verifica si el contenido de texto del elemento es válido según su tipo de datos para los elementos con contenido simple, y verifica si el contenido del elemento actual está completo para los elementos con contenido complejo.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del elemento. Este parámetro puede ser **nullptr**. |

### Valor devuelto

El valor de texto analizado y tipado del elemento si el elemento tiene contenido simple.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) método


Verifica si el contenido de texto del elemento especificado es válido según su tipo de datos.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | Un objeto [XmlSchemaInfo](../../xmlschemainfo/) cuyas propiedades se establecen tras la validación exitosa del contenido de texto del elemento. Este parámetro puede ser **nullptr**. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | El contenido de texto tipado del elemento. |

### Valor devuelto

El contenido simple analizado y tipado del elemento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)