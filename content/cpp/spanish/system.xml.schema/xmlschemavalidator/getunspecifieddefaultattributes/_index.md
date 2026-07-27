---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides para C++ Referencia de la API
description: "Valida las restricciones de identidad en los atributos predeterminados y rellena la List especificada con objetos XmlSchemaAttribute para cualquier atributo con valores predeterminados que no haya sido previamente validado usando el método XmlSchemaValidator::ValidateAttribute en el contexto del elemento."
type: docs
weight: 157
url: /es/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) método

Valida las restricciones de identidad en los atributos predeterminados y rellena la List especificada con objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para cualquier atributo con valores predeterminados que no haya sido previamente validado usando el método [XmlSchemaValidator::ValidateAttribute](../validateattribute/) en el contexto del elemento.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | Una List para rellenar con objetos [XmlSchemaAttribute](../../xmlschemaattribute/) para cualquier atributo que aún no se haya encontrado durante la validación en el contexto del elemento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [List](../../../system.collections.generic/list/)
* Clase [Object](../../../system/object/)
* Clase [XmlSchemaValidator](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)