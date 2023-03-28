---
title: get_LocalName()
second_title: Aspose.Slides for C++ API Reference
description: Returns the local name of the node, when overridden in a derived class.
type: docs
weight: 209
url: /cpp/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() method


Returns the local name of the node, when overridden in a derived class.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### Return Value

The name of the node with the prefix removed. For example, **LocalName** is **book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlNode::get_NodeType](../get_nodetype/) of the node: 

| Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| The local name of the attribute. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | The document type name. |
| Element | The local name of the element. |
| Entity | The name of the entity. |
| EntityReference | The name of the entity referenced. |
| Notation | The notation name. |
| ProcessingInstruction | The target of the processing instruction. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## See Also

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
