---
title: get_Value()
second_title: Aspose.Slides C++ API 参考
description: 返回当前节点的文本值。
type: docs
weight: 79
url: /zh/system.xml/xmlvalidatingreader/get_value/
---
## XmlValidatingReader::get_Value() 方法

返回当前节点的文本值。

```cpp
String System::Xml::XmlValidatingReader::get_Value() override
```

### 返回值

返回的值取决于节点的 XmlValidatingReader::NodeType。

## 备注

下表列出了具有可返回值的节点类型。所有其他节点类型返回 [String::Empty](../../../system/string/empty/)。

| 节点类型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的值。 |
| CDATA| CDATA 部分的内容。 |
| Comment| 注释的内容。 |
| DocumentType| 内部子集。 |
| ProcessingInstruction| 整个内容（不包括目标）。 |
| SignificantWhitespace| 混合内容模型中标记之间的空白。 |
| [Text](../../../system.text/)| 文本节点的内容。 |
| Whitespace| 标记之间的空白。 |
| [XmlDeclaration](../../xmldeclaration/)| 声明的内容。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)