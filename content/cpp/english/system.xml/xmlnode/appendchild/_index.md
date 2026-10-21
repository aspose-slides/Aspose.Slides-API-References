---
title: AppendChild()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified node to the end of the list of child nodes, of this node.
type: docs
weight: 443
url: /system.xml/xmlnode/appendchild/
---
## XmlNode::AppendChild(SharedPtr\<XmlNode\>) method


Adds the specified node to the end of the list of child nodes, of this node.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::AppendChild(SharedPtr<XmlNode> newChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | The node to add. All the contents of the node to be added are moved into the specified location. |

### Return Value

The node added.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | This node is of a type that does not allow child nodes of the type of the **newChild** node. The **newChild** is an ancestor of this node. |
| ArgumentException | The **newChild** was created from a different document than the one that created this node. This node is read-only. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)