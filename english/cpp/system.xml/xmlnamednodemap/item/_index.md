---
title: Item()
second_title: Aspose.Slides for C++ API Reference
description: Retrieves the node at the specified index in the XmlNamedNodeMap.
type: docs
weight: 53
url: /cpp/system.xml/xmlnamednodemap/item/
---
## XmlNamedNodeMap::Item(**int32_t**) method


Retrieves the node at the specified index in the [XmlNamedNodeMap](../).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::Item(int32_t index)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | The index position of the node to retrieve from the [XmlNamedNodeMap](../). The index is zero-based; therefore, the index of the first node is 0 and the index of the last node is [XmlNamedNodeMap::get_Count](../get_count/) - 1. |

### Return Value

The [XmlNode](../../xmlnode/) at the specified index. If **index** is less than 0 or greater than or equal to the [XmlNamedNodeMap::get_Count](../get_count/) value, **nullptr** is returned.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
