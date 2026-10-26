---
title: XmlNodeType
second_title: Aspose.Slides C++ API 参考
description: 指定节点的类型。
type: docs
weight: 833
url: /zh/system.xml/xmlnodetype/
---
## XmlNodeType 枚举

指定节点的类型。

```cpp
enum class XmlNodeType
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| None | 0 | 如果未调用 **Read** 方法，则 [XmlReader](../xmlreader/) 返回此值。 |
| Element | 1 | 一个元素（例如，**<item>**）。 |
| Attribute | 2 | 一个属性（例如，**id='123'**）。 |
| Text | 3 | 节点的文本内容。[XmlNodeType::Text](./) 节点不能有任何子节点。它可以作为 [XmlNodeType::Attribute](./)、[XmlNodeType::DocumentFragment](./)、[XmlNodeType::Element](./) 和 [XmlNodeType::EntityReference](./) 节点的子节点出现。 |
| CDATA | 4 | 一个 CDATA 区段（例如，**my escaped text**）。 |
| EntityReference | 5 | 对实体的引用（例如，**&num;**）。 |
| Entity | 6 | 一个实体声明（例如，**<!ENTITY...>**）。 |
| ProcessingInstruction | 7 | 一个处理指令（例如，**<?pi test?>**）。 |
| Comment | 8 | 一条注释（例如，****）。 |
| Document | 9 | 一个文档对象，作为文档树的根，提供对整个 XML 文档的访问。 |
| DocumentType | 10 | 文档类型声明，由以下标记指示（例如，**<!DOCTYPE...>**）。 |
| DocumentFragment | 11 | 一个文档片段。 |
| Notation | 12 | 文档类型声明中的一种标记（例如，**<!NOTATION...>**）。 |
| Whitespace | 13 | 标记之间的空白。 |
| SignificantWhitespace | 14 | 混合内容模型中标记之间的空白，或 **xml:space="preserve"** 范围内的空白。 |
| EndElement | 15 | 一个结束元素标记（例如，****）。 |
| EndEntity | 16 | 当 [XmlReader](../xmlreader/) 因调用 [XmlReader::ResolveEntity](../xmlreader/resolveentity/) 而到达实体替换的末尾时返回。 |
| XmlDeclaration | 17 | XML 声明（例如，**<?xml version='1.0'?>**）。[XmlNodeType::XmlDeclaration](./) 节点必须是文档中的第一个节点。它不能有子节点。它是 [XmlNodeType::Document](./) 节点的子节点。它可以具有提供版本和编码信息的属性。 |

## 另请参见

* 命名空间 [System::Xml](../)
* 库 [Aspose.Slides](../../)