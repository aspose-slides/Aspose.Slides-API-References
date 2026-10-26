---
title: get_LocalName()
second_title: Aspose.Slides for C++ API 参考
description: 当在派生类中重写时，返回节点的本地名称。
type: docs
weight: 209
url: /zh/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() 方法


当在派生类中重写时，返回节点的本地名称。

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```


### 返回值

去除前缀后的节点名称。例如，对于元素 **<bk:book>**，**LocalName** 为 **book**。

## 备注



返回的名称取决于节点的 [XmlNode::get_NodeType](../get_nodetype/)：

| 类型 | 名称 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的本地名称。 |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | 文档类型的名称。 |
| Element | 元素的本地名称。 |
| Entity | 实体的名称。 |
| EntityReference | 被引用实体的名称。 |
| Notation | 标记名称。 |
| ProcessingInstruction | 处理指令的目标。 |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |


## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)