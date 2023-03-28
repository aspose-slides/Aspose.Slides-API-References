---
title: Item()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves a node at the given index.
type: docs
weight: 14
url: /cpp/system.xml/xmlnodelist/item/
---
## XmlNodeList::Item(**int32_t**) method


Retrieves a node at the given index.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::Item(int32_t index)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The zero-based index into the list of nodes. |

### Return Value

The [XmlNode](../../xmlnode/) with the specified index in the collection. If **index** is greater than or equal to the number of nodes in the list, this returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
