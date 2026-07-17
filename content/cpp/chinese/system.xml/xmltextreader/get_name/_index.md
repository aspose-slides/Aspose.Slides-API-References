---
title: get_Name()
second_title: Aspose.Slides for C++ API 参考
description: 返回当前节点的限定名称。
type: docs
weight: 14
url: /zh/system.xml/xmltextreader/get_name/
---
## XmlTextReader::get_Name() 方法

Returns the qualified name of the current node.

```cpp
String System::Xml::XmlTextReader::get_Name() override
```

### 返回值

The qualified name of the current node. For example, **Name** is **bk:book** for the element **<bk:book>**.

## 备注

The name returned is dependent on the [XmlTextReader::get_NodeType](../get_nodetype/) value of the node. The following node types return the listed values. All other node types return an empty string. 

| 节点类型 | 名称 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的名称。 |
| DocumentType| 文档类型名称。 |
| Element| 标签名称。 |
| EntityReference| 被引用实体的名称。 |
| ProcessingInstruction| 处理指令的目标。 |
| [XmlDeclaration](../../xmldeclaration/)| 文字字符串 `xml`。 |

## 另请参阅

* 类 [String](../../../system/string/)
* 类 [XmlTextReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)