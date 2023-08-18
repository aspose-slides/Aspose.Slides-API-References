---
title: MoveToContent()
second_title: Aspose.Slides for C++ API Reference
description: "Checks whether the current node is a content (non-white space text, CDATA, Element, EndElement, EntityReference, or EndEntity) node. If the node is not a content node, the reader skips ahead to the next content node or end of file. It skips over nodes of the following type: ProcessingInstruction, DocumentType, Comment, Whitespace, or SignificantWhitespace."
type: docs
weight: 833
url: /system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() method


Checks whether the current node is a content (non-white space text, **CDATA**, **Element**, **EndElement**, **EntityReference**, or **EndEntity**) node. If the node is not a content node, the reader skips ahead to the next content node or end of file. It skips over nodes of the following type: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, or **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```


### Return Value

The [XmlReader::get_NodeType](../get_nodetype/) value of the current node found by the method or [XmlNodeType::None](../../xmlnodetype/) if the reader has reached the end of the input stream.

## See Also

* Enum [XmlNodeType](../../xmlnodetype/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)