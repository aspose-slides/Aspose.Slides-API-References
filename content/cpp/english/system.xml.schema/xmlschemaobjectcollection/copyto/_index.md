---
title: CopyTo()
second_title: Aspose.Slides for C++ API Reference
description: Copies all the XmlSchemaObjects from the collection into the given array, starting at the given index.
type: docs
weight: 118
url: /system.xml.schema/xmlschemaobjectcollection/copyto/
---
## XmlSchemaObjectCollection::CopyTo(const ArrayPtr\<SharedPtr\<XmlSchemaObject\>\>&, int32_t) method


Copies all the XmlSchemaObjects from the collection into the given array, starting at the given index.

```cpp
void System::Xml::Schema::XmlSchemaObjectCollection::CopyTo(const ArrayPtr<SharedPtr<XmlSchemaObject>> &array, int32_t index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| array | const [ArrayPtr](../../../system/arrayptr/)\<[SharedPtr](../../../system/sharedptr/)\<[XmlSchemaObject](../../xmlschemaobject/)\>\>& | The array that is the destination of the elements copied from the [XmlSchemaObjectCollection](../). The array must have zero-based indexing. |
| index | **int32_t** | The zero-based index in the array at which copying begins. |

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentNullException | **array** is **nullptr**. |
| ArgumentOutOfRangeException | **index** is less than zero. |
| ArgumentException | **array** is multi-dimensional. or **index** is equal to or greater than the length of **array**. or The number of elements in the source [XmlSchemaObject](../../xmlschemaobject/) is greater than the available space from index to the end of the destination array. |
| InvalidCastException | The type of the source [XmlSchemaObject](../../xmlschemaobject/) cannot be cast automatically to the type of the destination array. |


## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaObject](../../xmlschemaobject/)
* Class [XmlSchemaObjectCollection](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)