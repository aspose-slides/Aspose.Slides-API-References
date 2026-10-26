---
title: Reprocess()
second_title: Referencia de la API de Aspose.Slides para C++
description: Vuelve a procesar un esquema de lenguaje de definición de XML Schema (XSD) que ya existe en el XmlSchemaSet.
type: docs
weight: 222
url: /es/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) método


Vuelve a procesar un esquema XML [Schema](../../) lenguaje de definición (XSD) que ya existe en el [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | El esquema a volver a procesar. |

### Valor devuelto

Un objeto [XmlSchema](../../xmlschema/) si el esquema es un esquema válido. Si el esquema no es válido y se especifica un ValidationEventHandler, **nullptr** se devuelve y se genera el evento de validación correspondiente. De lo contrario, se lanza una XmlSchemaException.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlSchema](../../xmlschema/)
* Clase [XmlSchemaSet](../)
* Espacio de nombres [System::Xml::Schema](../../)
* Biblioteca [Aspose.Slides](../../../)