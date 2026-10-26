---
title: get_Value()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，获取当前节点的文本值。
type: docs
weight: 92
url: /zh/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() 方法

When overridden in a derived class, gets the text value of the current node.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### 返回值

The value returned depends on the [XmlReader::get_NodeType](../get_nodetype/) value of the node.

## 备注

The following table lists node types that have a value to return. All other node types return [String::Empty](../../../system/string/empty/). 

| Node type | Value |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 属性的值。 |
| `CDATA`| CDATA 部分的内容。 |
| `Comment`| 注释的内容。 |
| `DocumentType`| 内部子集。 |
| `ProcessingInstruction`| 完整内容，不包括目标。 |
| `SignificantWhitespace`| 混合内容模型中标记之间的空白。 |
| `[Text](../../../system.text/)`| 文本节点的内容。 |
| `Whitespace`| 标记之间的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 声明的内容。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)