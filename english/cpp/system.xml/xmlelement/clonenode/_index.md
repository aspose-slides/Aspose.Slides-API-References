---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node.
type: docs
weight: 196
url: /cpp/system.xml/xmlelement/clonenode/
---
## XmlElement::CloneNode(bool) method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlElement::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself (and its attributes if the node is an [XmlElement](../)). |

### Return Value

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlElement](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)