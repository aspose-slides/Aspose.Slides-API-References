---
title: CloneNode()
second_title: Aspose.Slides for C++ API Reference
description: Creates a duplicate of this node.
type: docs
weight: 118
url: /cpp/system.xml/xmldocumenttype/clonenode/
---
## XmlDocumentType::CloneNode(**bool**) method


Creates a duplicate of this node.

```cpp
SharedPtr<XmlNode> System::Xml::XmlDocumentType::CloneNode(bool deep) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| deep | **bool** | **true** to recursively clone the subtree under the specified node; **false** to clone only the node itself. For document type nodes, the cloned node always includes the subtree, regardless of the parameter setting. |

### Return Value

The cloned node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlNode](../../xmlnode/)
* Class [XmlDocumentType](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
