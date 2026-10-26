---
title: get_SchemaInfo()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve la información del esquema que se ha asignado al nodo actual como resultado de la validación del esquema.
type: docs
weight: 196
url: /es/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() método

Devuelve la información del esquema que se ha asignado al nodo actual como resultado de la validación del esquema.

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### Valor devuelto

Un objeto IXmlSchemaInfo que contiene la información del esquema para el nodo actual. [Schema](../../../system.xml.schema/) información puede establecerse en elementos, atributos o en nodos de texto con un valor [XmlReader::get_ValueType](../get_valuetype/) no nulo. Si el nodo actual no es uno de los tipos de nodo anteriores, o si la instancia [XmlReader](../) no informa de la información del esquema, este método devuelve **nullptr**. Si este método se llama desde un objeto [XmlTextReader](../../xmltextreader/) o un objeto [XmlValidatingReader](../../xmlvalidatingreader/), este método siempre devuelve **nullptr**. Estas implementaciones [XmlReader](../) no exponen la información del esquema a través del método get_SchemaInfo.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)