---
title: get_Name()
second_title: Aspose.Slides C++ API 参考
description: 返回当前节点的限定名称。
type: docs
weight: 14
url: /zh/system.xml/xmlvalidatingreader/get_name/
---
## XmlValidatingReader::get_Name() 方法


返回当前节点的限定名称。

```cpp
String System::Xml::XmlValidatingReader::get_Name() override
```


### 返回值

当前节点的限定名称。例如，**Name** 对于元素 **<bk:book>** 为 **bk:book**。
## 备注



返回的名称取决于节点的 XmlValidatingReader::NodeType。以下节点类型返回相应的值。所有其他节点类型返回空字符串。 

| 节点类型 | 名称 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的名称。 |
| DocumentType| 文档类型名称。 |
| Element| 标签名称。 |
| EntityReference| 被引用实体的名称。 |
| ProcessingInstruction| 处理指令的目标。 |
| [XmlDeclaration](../../xmldeclaration/)| 字面字符串 `xml`。 |


## 另请参见

* 类 [String](../../../system/string/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)