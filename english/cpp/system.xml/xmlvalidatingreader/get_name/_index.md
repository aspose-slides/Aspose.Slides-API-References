---
title: get_Name()
second_title: Aspose.Slides for C++ API Reference
description: Returns the qualified name of the current node.
type: docs
weight: 14
url: /cpp/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() method


Returns the qualified name of the current node.

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### Return Value

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.
## Remarks



The name returned is dependent on the XmlValidatingReader::NodeType of the node. The following node types return the listed values. All other node types return an empty string. 

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
* Class [XmlValidatingReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)
