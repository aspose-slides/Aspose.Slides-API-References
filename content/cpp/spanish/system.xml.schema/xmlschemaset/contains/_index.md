---
title: Contains()
second_title: Referencia de API de Aspose.Slides para C++
description: Indica si un esquema de lenguaje de definición de XML Schema (XSD) con el URI de espacio de nombres de destino especificado está en el XmlSchemaSet.
type: docs
weight: 196
url: /es/system.xml.schema/xmlschemaset/contains/
---
## XmlSchemaSet::Contains(String) método


Indica si un esquema de lenguaje de definición XML [Schema](../../) (XSD) con el espacio de nombres de destino especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(String targetNamespace)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetNamespace | [String](../../../system/string/) | La propiedad **targetNamespace** del esquema. |

### Valor devuelto

**true** si un esquema con el espacio de nombres de destino especificado está en el [XmlSchemaSet](../); de lo contrario, **false**.

## XmlSchemaSet::Contains(const SharedPtr\<XmlSchema\>\&) método


Indica si el objeto [Schema](../../) de lenguaje de definición XML (XSD) [XmlSchema](../../xmlschema/) especificado está en el [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::Contains(const SharedPtr<XmlSchema> &schema)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | El objeto [XmlSchema](../../xmlschema/). |

### Valor devuelto

**true** si el objeto [XmlSchema](../../xmlschema/) está en el [XmlSchemaSet](../); de lo contrario, **false**.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [String](../../../system/string/)
* Clase [XmlSchemaSet](../)
* Clase [XmlSchema](../../xmlschema/)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)