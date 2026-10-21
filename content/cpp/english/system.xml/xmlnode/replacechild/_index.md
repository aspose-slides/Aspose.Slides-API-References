---
title: ReplaceChild()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the child node oldChild with newChild node.
type: docs
weight: 404
url: /system.xml/xmlnode/replacechild/
---
## XmlNode::ReplaceChild(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Replaces the child node **oldChild** with **newChild** node.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::ReplaceChild(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> oldChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | The new node to put in the child list. |
| oldChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | The node being replaced in the list. |

### Return Value

The node replaced.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | This node is of a type that does not allow child nodes of the type of the **newChild** node. The **newChild** is an ancestor of this node. |
| ArgumentException | The **newChild** was created from a different document than the one that created this node. This node is read-only. The **oldChild** is not a child of this node. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)