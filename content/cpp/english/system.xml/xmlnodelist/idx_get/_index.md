---
title: idx_get()
second_title: Aspose.Slides for C++ API Reference
description: Returns a node at the given index.
type: docs
weight: 40
url: /system.xml/xmlnodelist/idx_get/
---
## XmlNodeList::idx_get(int32_t) method


Returns a node at the given index.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNodeList::idx_get(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The zero-based index into the list of nodes. |

### Return Value

The [XmlNode](../../xmlnode/) with the specified index in the collection. If index is greater than or equal to the number of nodes in the list, this returns **nullptr**.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNodeList](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)