---
title: get_Value()
second_title: Aspose.Slides for C++ API Reference
description: Returns the value of the node.
type: docs
weight: 14
url: /cpp/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() method


Returns the value of the node.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```


### Return Value

The value returned depends on the [XmlNode::get_NodeType](../get_nodetype/) of the node: 

| Type | Value |
| --- | --- |
| [Attribute](../../../system/attribute/)| The value of the attribute. |
| CDATASection | The content of the CDATA Section. |
| Comment | The content of the comment. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. You can use the XmlElement::InnerText or [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) values to access the value of the element node. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | The entire content excluding the target. |
| [Text](../../../system.text/)| The content of the text node. |
| SignificantWhitespace | The white space characters. White space can consist of one or more space characters, carriage returns, line feeds, or tabs. |
| Whitespace | The white space characters. White space can consist of one or more space characters, carriage returns, line feeds, or tabs. |
| [XmlDeclaration](../../xmldeclaration/)| The content of the declaration (that is, everything between `<?xml and ?>`). |

## See Also

* Class [String](../../../system/string/)
* Class [XmlNode](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
