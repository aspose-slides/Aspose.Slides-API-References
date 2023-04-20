---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an XmlEntity object throws an exception.
type: docs
weight: 170
url: /cpp/system.xml/xmlentity/clonenode/
---
## XmlEntity::CloneNode(bool) method


Creates a duplicate of this node. Entity nodes cannot be cloned. Calling this method on an [XmlEntity](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlEntity::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. |

### Return Value

A copy of the [XmlNode](../../xmlnode/) from which the method is called.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlEntity](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)