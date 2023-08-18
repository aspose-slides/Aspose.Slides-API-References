---
title: get_SchemaType()
second_title: Aspose.Slides for C++ API Reference
description: Returns a schema type object.
type: docs
weight: 287
url: /system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() method


Returns a schema type object.

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```


### Return Value

XmlSchemaDatatype, XmlSchemaSimpleType, or XmlSchemaComplexType depending whether the node value is a built in XML [Schema](../../../system.xml.schema/) definition language (XSD) type or a user defined simpleType or complexType; **nullptr** if the current node has no schema type.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)