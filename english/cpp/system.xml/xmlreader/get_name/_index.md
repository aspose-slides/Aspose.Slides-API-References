---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: When overridden in a derived class, gets the qualified name of the current node.
type: docs
weight: 27
url: /cpp/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() method


When overridden in a derived class, gets the qualified name of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Name()
```


### Return Value

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| Node type | Name |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| The name of the attribute. |
| `DocumentType`| The document type name. |
| `Element`| The tag name. |
| `EntityReference`| The name of the entity referenced. |
| `ProcessingInstruction`| The target of the processing instruction. |
| [XmlDeclaration](../../xmldeclaration/)| The literal string `xml`. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
