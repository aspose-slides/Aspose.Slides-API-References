---
title: AppendChild()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified node to the end of the list of child nodes, of this node.
type: docs
weight: 274
url: /system.xml/xmlattribute/appendchild/
---
## XmlAttribute::AppendChild(SharedPtr\<XmlNode\>) method


Adds the specified node to the end of the list of child nodes, of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::AppendChild(SharedPtr<XmlNode> newChild) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) to add. |

### Return Value

The [XmlNode](../../xmlnode/) added.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | This node is of a type that does not allow child nodes of the type of the **newChild** node. The **newChild** is an ancestor of this node. |
| ArgumentException | The **newChild** was created from a different document than the one that created this node. This node is read-only. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)