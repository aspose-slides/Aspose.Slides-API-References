---
title: Reprocess()
second_title: Aspose.Slides for C++ API Reference
description: Reprocesses an XML Schema definition language (XSD) schema that already exists in the XmlSchemaSet.
type: docs
weight: 222
url: /system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) method


Reprocesses an XML [Schema](../../) definition language (XSD) schema that already exists in the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | The schema to reprocess. |

### Return Value

An [XmlSchema](../../xmlschema/) object if the schema is a valid schema. If the schema is not valid and a ValidationEventHandler is specified, **nullptr** is returned and the appropriate validation event is raised. Otherwise, an XmlSchemaException is thrown.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)