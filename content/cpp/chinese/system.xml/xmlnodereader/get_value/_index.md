---
title: get_Value()
second_title: Aspose.Slides C++ API 参考
description: 返回当前节点的文本值。
type: docs
weight: 79
url: /zh/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() 方法

返回当前节点的文本值。

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### 返回值

返回的值取决于节点的[XmlNodeReader::get_NodeType](../get_nodetype/)。

## 备注

下表列出了具有返回值的节点类型。所有其他节点类型返回[String::Empty](../../../system/string/empty/)。

| 节点类型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的值。 |
| CDATA| CDATA 部分的内容。 |
| Comment| 注释的内容。 |
| DocumentType| 内部子集。 |
| ProcessingInstruction| 完整内容，不包括目标。 |
| SignificantWhitespace| 混合内容模型中标记之间的空白。 |
| [Text](../../../system.text/)| 文本节点的内容。 |
| Whitespace| 标记之间的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 声明的内容。 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)