---
title: IsDerivedFrom()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un valor que indica si el tipo de esquema derivado especificado está derivado del tipo de esquema base especificado.
type: docs
weight: 209
url: /es/system.xml.schema/xmlschematype/isderivedfrom/
---
## XmlSchemaType::IsDerivedFrom(SharedPtr\<XmlSchemaType\>, const SharedPtr\<XmlSchemaType\>\&, XmlSchemaDerivationMethod) método


Devuelve un valor que indica si el tipo de esquema derivado especificado está derivado del tipo de esquema base especificado.

```cpp
static bool System::Xml::Schema::XmlSchemaType::IsDerivedFrom(SharedPtr<XmlSchemaType> derivedType, const SharedPtr<XmlSchemaType> &baseType, XmlSchemaDerivationMethod except)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| derivedType | [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\> | El [XmlSchemaType](../) derivado a probar. |
| baseType | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaType](../)\>\& | El [XmlSchemaType](../) base para probar el [XmlSchemaType](../) derivado. |
| except | [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/) | Uno de los valores de XmlSchemaDerivationMethod que representa un método de derivación de tipo a excluir de la prueba. |

### Valor de retorno

**true** si el tipo derivado está derivado del tipo base; de lo contrario, **false**.

## Ver también

* Enum [XmlSchemaDerivationMethod](../../xmlschemaderivationmethod/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchemaType](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)