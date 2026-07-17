---
title: get_Value()
second_title: Aspose.Slides for C++ API 参考
description: 返回节点的值。
type: docs
weight: 14
url: /zh/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() 方法

返回节点的值。

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### 返回值

返回的值取决于节点的 [XmlNode::get_NodeType](../get_nodetype/)：

| 类型 | 值 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的值。 |
| CDATASection | CDATA 节的内容。 |
| Comment | 注释的内容。 |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. 您可以使用 XmlElement::InnerText 或 [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) 值来访问元素节点的值。 |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | 除目标外的全部内容。 |
| [Text](../../../system.text/)| 文本节点的内容。 |
| SignificantWhitespace | 空白字符。空白可以由一个或多个空格字符、回车、换行或制表符组成。 |
| Whitespace | 空白字符。空白可以由一个或多个空格字符、回车、换行或制表符组成。 |
| [XmlDeclaration](../../xmldeclaration/)| 声明的内容（即 `<?xml` 和 `?>` 之间的所有内容）。 |

## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlNode](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)