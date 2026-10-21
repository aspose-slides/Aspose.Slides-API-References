---
title: PrependChild()
second_title: Aspose.Slides for C++ API Reference
description: Adds the specified node to the beginning of the list of child nodes for this node.
type: docs
weight: 261
url: /system.xml/xmlattribute/prependchild/
---
## XmlAttribute::PrependChild(SharedPtr\<XmlNode\>) method


Adds the specified node to the beginning of the list of child nodes for this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::PrependChild(SharedPtr<XmlNode> newChild) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) to add. If it is an [XmlDocumentFragment](../../xmldocumentfragment/), the entire contents of the document fragment are moved into the child list of this node. |

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