---
title: get_SchemaType()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve un objeto de tipo de esquema.
type: docs
weight: 287
url: /es/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() método

Devuelve un objeto de tipo de esquema.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```

### Valor devuelto

XmlSchemaDatatype, XmlSchemaSimpleType o XmlSchemaComplexType dependiendo de si el valor del nodo es un tipo incorporado del lenguaje de definición XML [Schema](../../../system.xml.schema/) (XSD) o un simpleType o complexType definido por el usuario; **nullptr** si el nodo actual no tiene tipo de esquema.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)