---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API Reference
description: Removes the specified XML Schema definition language (XSD) schema and all the schemas it imports from the XmlSchemaSet.
type: docs
weight: 183
url: /cpp/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\&) method


Removes the specified XML [Schema](../../) definition language (XSD) schema and all the schemas it imports from the [XmlSchemaSet](../).

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | The [XmlSchema](../../xmlschema/) object to remove from the [XmlSchemaSet](../). |

### Return Value

**true** if the [XmlSchema](../../xmlschema/) object and all its imports were successfully removed; otherwise, **false**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchema](../../xmlschema/)
* Class [XmlSchemaSet](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
