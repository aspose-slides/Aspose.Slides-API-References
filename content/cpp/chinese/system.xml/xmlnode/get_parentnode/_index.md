---
title: get_ParentNode()
second_title: Aspose.Slides for C++ API 参考
description: 返回此节点的父节点（适用于能够拥有父节点的节点）。
type: docs
weight: 53
url: /zh/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() 方法

Returns the parent of this node (for nodes that can have parents).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### 返回值

当前节点的父节点 [XmlNode](../)。

## 备注

如果节点刚刚被创建且尚未添加到树中，或者已经从树中移除，则其父节点为 **nullptr**。对所有其他节点，返回的值取决于节点的 [XmlNode::get_NodeType](../get_nodetype/)。以下表格描述了 **get_NodeType** 方法可能的返回值。

| NodeType | ParentNode 的返回值 |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | 返回 `nullptr`；这些节点没有父节点。 |
| CDATA | 返回包含 CDATA 节的元素或实体引用。 |
| Comment | 返回包含注释的元素、实体引用、文档类型或文档。 |
| DocumentType | 返回文档节点。 |
| Element | 返回元素的父节点。如果该元素是树中的根节点，父节点是文档节点。 |
| EntityReference | 返回包含实体引用的元素、属性或实体引用。 |
| ProcessingInstruction | 返回包含处理指令的文档、元素、文档类型或实体引用。 |
| [Text](../../../system.text/) | 返回包含文本节点的父元素、属性或实体引用。 |

## 另见

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)