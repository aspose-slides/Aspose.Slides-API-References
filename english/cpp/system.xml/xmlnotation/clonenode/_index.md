---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an XmlNotation object throws an exception.
type: docs
weight: 118
url: /cpp/system.xml/xmlnotation/clonenode/
---
## XmlNotation::CloneNode(bool) method


Creates a duplicate of this node. Notation nodes cannot be cloned. Calling this method on an [XmlNotation](../) object throws an exception.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNotation::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. |

### Return Value

A [XmlNode](../../xmlnode/) copy of the node from which the method is called.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNotation](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)