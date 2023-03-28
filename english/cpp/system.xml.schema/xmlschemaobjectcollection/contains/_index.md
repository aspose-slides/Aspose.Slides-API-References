---
title: Contains()
second_title: Aspose.Slides for C++ API Reference
description: Indicates if the specified XmlSchemaObject is in the XmlSchemaObjectCollection.
type: docs
weight: 92
url: /cpp/system.xml.schema/xmlschemaobjectcollection/contains/
---
## XmlSchemaObjectCollection::Contains(const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\&) method


Indicates if the specified [XmlSchemaObject](../../xmlschemaobject/) is in the [XmlSchemaObjectCollection](../).

```cpp
bool System::Xml::Schema::XmlSchemaObjectCollection::Contains(const SharedPtr<XmlSchemaObject> &item)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| item | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\& | The [XmlSchemaObject](../../xmlschemaobject/). |

### Return Value

**true** if the specified qualified name is in the collection; otherwise, returns **false**. If **nullptr** is supplied, **false** is returned because there is no qualified name with a null name.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)
