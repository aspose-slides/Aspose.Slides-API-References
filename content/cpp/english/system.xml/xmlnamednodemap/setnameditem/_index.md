---
title: SetNamedItem()
second_title: Aspose.Slides for C++ API Reference
description: "Adds an XmlNode using its XmlNode::get_Name value."
type: docs
weight: 27
url: /system.xml/xmlnamednodemap/setnameditem/
---
## XmlNamedNodeMap::SetNamedItem(SharedPtr\<XmlNode\>) method


Adds an [XmlNode](../../xmlnode/) using its [XmlNode::get_Name](../../xmlnode/get_name/) value.

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNamedNodeMap::SetNamedItem(SharedPtr<XmlNode> node)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| node | [SharedPtr](../../../system/sharedptr/)\<[XmlNode](../../xmlnode/)\> | An [XmlNode](../../xmlnode/) to store in the [XmlNamedNodeMap](../). If a node with that name is already present in the map, it is replaced by the new one. |

### Return Value

If the **node** replaces an existing node with the same name, the old node is returned; otherwise, **nullptr** is returned.

### Exceptions

| Exception | Description |
| --- | --- |
| ArgumentException | The **node** was created from a different [XmlDocument](../../xmldocument/) than the one that created the [XmlNamedNodeMap](../); or the [XmlNamedNodeMap](../) is read-only. |


## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlNamedNodeMap](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)