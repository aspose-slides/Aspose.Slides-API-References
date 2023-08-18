---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: Returns the qualified name of the current node.
type: docs
weight: 14
url: /system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() method


Returns the qualified name of the current node.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```


### Return Value

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the [XmlTextReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| Node Type | Name |
| --- | --- |
| [Attribute](../../../system/attribute/)| The name of the attribute. |
| DocumentType| The document type name. |
| Element| The tag name. |
| EntityReference| The name of the entity referenced. |
| ProcessingInstruction| The target of the processing instruction. |
| [XmlDeclaration](../../xmldeclaration/)| The literal string `xml`. |


## See Also

* Class [String](../../../system/string/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)