---
title: Schemas()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve una colección de todos los esquemas del lenguaje de definición XML Schema (XSD) en el XmlSchemaSet.
type: docs
weight: 248
url: /es/system.xml.schema/xmlschemaset/schemas/
---
## XmlSchemaSet::Schemas() método


Devuelve una colección de todos los esquemas de lenguaje de definición XML [Schema](../../) (XSD) en el [XmlSchemaSet](../).

```cpp
SharedPtr<Collections::Generic::IList<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas()
```


### Valor de retorno

Un objeto IList que contiene todos los esquemas que se han añadido al [XmlSchemaSet](../). Si no se han añadido esquemas al [XmlSchemaSet](../), se devuelve una colección vacía.

## XmlSchemaSet::Schemas(String) método


Devuelve una colección de todos los esquemas de lenguaje de definición XML [Schema](../../) (XSD) en el [XmlSchemaSet](../) que pertenecen al espacio de nombres dado.

```cpp
SharedPtr<Collections::Generic::List<SharedPtr<XmlSchema>>> System::Xml::Schema::XmlSchemaSet::Schemas(String targetNamespace)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La propiedad **targetNamespace** del esquema. |

### Valor de retorno

Un objeto IList que contiene todos los esquemas que se han añadido al [XmlSchemaSet](../) que pertenecen al espacio de nombres dado. Si no se han añadido esquemas al [XmlSchemaSet](../), se devuelve una colección vacía.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IList](../../../system.collections.generic/ilist/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [XmlSchemaSet](../)
* Clase [List](../../../system.collections.generic/list/)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)