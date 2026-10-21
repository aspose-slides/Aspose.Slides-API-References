---
title: ReplaceChild()
second_title: Aspose.Slides for C++ API Reference
description: Replaces the child node specified with the new child node specified.
type: docs
weight: 235
url: /system.xml/xmlattribute/replacechild/
---
## XmlAttribute::ReplaceChild(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Replaces the child node specified with the new child node specified.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::ReplaceChild(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> oldChild) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The new child [XmlNode](../../xmlnode/). |
| oldChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) to replace. |

### Return Value

The [XmlNode](../../xmlnode/) replaced.

### Exceptions

| Exception | Description |
| --- | --- |
| InvalidOperationException | This node is of a type that does not allow child nodes of the type of the **newChild** node. The **newChild** is an ancestor of this node. |
| ArgumentException | The **newChild** was created from a different document than the one that created this node. This node is read-only. The **oldChild** is not a child of this node. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)