---
title: get_Name()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，返回节点的限定名称。
type: docs
weight: 1
url: /zh/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() 方法

当在派生类中重写时，返回节点的限定名称。

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### 返回值

节点的限定名称。

## 备注

返回的名称取决于[XmlNode::get_NodeType](../get_nodetype/)的节点：

| 类型 | 名称 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的限定名称。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 文档类型名称。 |
| Element | 元素的限定名称。 |
| Entity | 实体的名称。 |
| EntityReference | 被引用实体的名称。 |
| Notation | 标记名称。 |
| ProcessingInstruction | 处理指令的目标。 |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)