---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node.
type: docs
weight: 79
url: /system.xml/xmlsignificantwhitespace/clonenode/
---
## XmlSignificantWhitespace::CloneNode(bool) method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlSignificantWhitespace::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For significant white space nodes, the cloned node always includes the data value, regardless of the parameter setting. |

### Return Value

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlSignificantWhitespace](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)