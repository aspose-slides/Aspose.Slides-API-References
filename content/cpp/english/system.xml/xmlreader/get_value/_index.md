---
title: get_Value()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, gets the text value of the current node.
type: docs
weight: 92
url: /system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() method


When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```


### Return Value

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.
## Remarks



The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| The value of the attribute. |
| `CDATA`| The content of the CDATA section. |
| `Comment`| The content of the comment. |
| `DocumentType`| The internal subset. |
| `ProcessingInstruction`| The entire content, excluding the target. |
| `SignificantWhitespace`| The white space between markup in a mixed content model. |
| `[Text](../../../system.text/)`| The content of the text node. |
| `Whitespace`| The white space between markup. |
| [XmlDeclaration](../../xmldeclaration/)| The content of the declaration. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)