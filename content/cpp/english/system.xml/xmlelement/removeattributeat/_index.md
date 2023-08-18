---
title: RemoveAttributeAt()
second_title: Aspose.Slides for C++ API Reference
description: Removes the attribute node with the specified index from the element. (If the removed attribute has a default value, it is immediately replaced).
type: docs
weight: 339
url: /system.xml/xmlelement/removeattributeat/
---
## XmlElement::RemoveAttributeAt(int32_t) method


Removes the attribute node with the specified index from the element. (If the removed attribute has a default value, it is immediately replaced).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlElement::RemoveAttributeAt(int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **int32_t** | The index of the node to remove. The first node has index 0. |

### Return Value

The attribute node removed or **nullptr** if there is no node at the given index.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)