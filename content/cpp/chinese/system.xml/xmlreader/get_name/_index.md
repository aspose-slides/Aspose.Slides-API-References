---
title: get_Name()
second_title: Aspose.Slides for C++ API 参考
description: 在派生类中重写时，获取当前节点的限定名称。
type: docs
weight: 27
url: /zh/system.xml/xmlreader/get_name/
---
## XmlReader::get_Name() 方法

当在派生类中重写时，获取当前节点的限定名称。

```cpp
virtual String System::Xml::XmlReader::get_Name()
```

### 返回值

当前节点的限定名称。例如，元素 **<bk:book>** 的 **Name** 为 **bk:book**。

## 备注

返回的名称取决于节点的 [XmlReader::get_NodeType](../get_nodetype/) 值。以下节点类型返回列出的值。所有其他节点类型返回空字符串。

| 节点类型 | 名称 |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| 属性的名称。 |
| `DocumentType`| 文档类型名称。 |
| `Element`| 标记名称。 |
| `EntityReference`| 被引用实体的名称。 |
| `ProcessingInstruction`| 处理指令的目标。 |
| [XmlDeclaration](../../xmldeclaration/)| 字面字符串 `xml`。 |

## 另见

* 类 [String](../../../system/string/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)