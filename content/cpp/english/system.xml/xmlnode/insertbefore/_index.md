---
title: InsertBefore()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the specified node immediately before the specified reference node.
type: docs
weight: 378
url: /system.xml/xmlnode/insertbefore/
---
## XmlNode::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Inserts the specified node immediately before the specified reference node.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | The node to insert. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../)\> | The reference node. **newChild** is placed before this node. |

### Return Value

The node being inserted.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | The current node is of a type that does not allow child nodes of the type of the **newChild** node. The **newChild** is an ancestor of this node. |
| ArgumentException | The **newChild** was created from a different document than the one that created this node. The **refChild** is not a child of this node. This node is read-only. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)