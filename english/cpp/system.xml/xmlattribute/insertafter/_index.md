---
title: InsertAfter()
second_title: Aspose.Slides for C++ API Reference
description: Inserts the specified node immediately after the specified reference node.
type: docs
weight: 222
url: /cpp/system.xml/xmlattribute/insertafter/
---
## XmlAttribute::InsertAfter(SharedPtr\<XmlNode\>, SharedPtr\<XmlNode\>) method


Inserts the specified node immediately after the specified reference node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlAttribute::InsertAfter(SharedPtr<XmlNode> newChild, SharedPtr<XmlNode> refChild) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) to insert. |
| refChild | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | The [XmlNode](../../xmlnode/) that is the reference node. The **newChild** is placed after the **refChild**. |

### Return Value

The [XmlNode](../../xmlnode/) inserted.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlAttribute](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)