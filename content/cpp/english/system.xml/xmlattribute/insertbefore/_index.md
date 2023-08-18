---
title: InsertBefore()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the specified node immediately before the specified reference node.
type: docs
weight: 209
url: /system.xml/xmlattribute/insertbefore/
---
## XmlAttribute::InsertBefore(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Inserts the specified node immediately before the specified reference node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertBefore(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) to insert. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) that is the reference node. The **newChild** is placed before this node. |

### Return Value

The [XmlNode](../../xmlnode/) inserted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)