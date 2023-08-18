---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes the specified XML Schema definition language (XSD) schema from the XmlSchemaSet.
type: docs
weight: 170
url: /system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) method


Removes the specified XML [Schema](../../) definition language (XSD) schema from the [XmlSchemaSet](../).

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) object to remove from the [XmlSchemaSet](../). |

### Return Value

The [XmlSchema](../../xmlschema/) object removed from the [XmlSchemaSet](../) or **nullptr** if the schema was not found in the [XmlSchemaSet](../).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)