---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node.
type: docs
weight: 40
url: /cpp/system.xml/xmlcomment/clonenode/
---
## XmlComment::CloneNode(**bool**) method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlComment::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. Because comment nodes do not have children, the cloned node always includes the text content, regardless of the parameter setting. |

### Return Value

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlComment](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
