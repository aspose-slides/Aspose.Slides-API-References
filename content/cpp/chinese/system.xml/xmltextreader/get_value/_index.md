---
title: get_Value()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前节点的文本值。
type: docs
weight: 79
url: /zh/system.xml/xmltextreader/get_value/
---
## XmlTextReader::get_Value() 方法

返回当前节点的文本值。

```cpp
String System::Xml::XmlTextReader::get_Value() override
```

### 返回值

返回的值取决于节点的 [XmlTextReader::get_NodeType](../get_nodetype/) 值。

## 备注

下表列出了具有可返回值的节点类型。所有其他节点类型返回 [String::Empty](../../../system/string/empty/)。

| 节点类型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| The value of the attribute. |
| CDATA| The content of the CDATA section. |
| Comment| The content of the comment. |
| DocumentType| The internal subset. |
| ProcessingInstruction| The entire content, excluding the target. |
| SignificantWhitespace| The white space within an `xml:space='preserve'` scope. |
| [Text](../../../system.text/)| The content of the text node. |
| Whitespace| The white space between markup. |
| [XmlDeclaration](../../xmldeclaration/)| The content of the declaration. |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)