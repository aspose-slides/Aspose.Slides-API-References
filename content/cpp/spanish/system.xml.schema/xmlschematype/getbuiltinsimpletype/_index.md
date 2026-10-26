---
title: GetBuiltInSimpleType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un XmlSchemaSimpleType que representa el tipo simple incorporado del tipo simple que se especifica mediante el nombre calificado.
type: docs
weight: 183
url: /es/system.xml.schema/xmlschematype/getbuiltinsimpletype/
---
## XmlSchemaType::GetBuiltInSimpleType(const SharedPtr\<XmlQualifiedName\>\&) método


Devuelve un [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple que se especifica mediante el nombre calificado.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(const SharedPtr<XmlQualifiedName> &qualifiedName)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| qualifiedName | const [SharedPtr](../../../system/sharedptr/)\<[XmlQualifiedName](../../../system.xml/xmlqualifiedname/)\>\& | El [XmlQualifiedName](../../../system.xml/xmlqualifiedname/) del tipo simple. |

### Valor de retorno

El [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa el tipo simple incorporado.

## XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode) método


Devuelve un [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa el tipo simple incorporado del tipo simple especificado.

```cpp
static SharedPtr<XmlSchemaSimpleType> System::Xml::Schema::XmlSchemaType::GetBuiltInSimpleType(XmlTypeCode typeCode)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| typeCode | [XmlTypeCode](../../xmltypecode/) | Uno de los valores de XmlTypeCode que representa el tipo simple. |

### Valor de retorno

El [XmlSchemaSimpleType](../../xmlschemasimpletype/) que representa el tipo simple incorporado.

## Ver también

* Enumeración [XmlTypeCode](../../xmltypecode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchemaSimpleType](../../xmlschemasimpletype/)
* Clase [XmlQualifiedName](../../../system.xml/xmlqualifiedname/)
* Clase [XmlSchemaType](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)