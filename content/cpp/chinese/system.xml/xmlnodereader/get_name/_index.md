---
title: get_Name()
second_title: Aspose.Slides C++ API 参考
description: 返回当前节点的限定名称。
type: docs
weight: 14
url: /zh/system.xml/xmlnodereader/get_name/
---
## XmlNodeReader::get_Name() 方法


返回当前节点的限定名称。

```cpp
String System::Xml::XmlNodeReader::get_Name() override
```


### Return Value

当前节点的限定名称。例如，**Name** 为 **bk:book**，对应元素 **<bk:book>**.
## Remarks



返回的名称取决于节点的 [XmlNodeReader::get_NodeType](../get_nodetype/) 值。以下节点类型返回列出的值。其他所有节点类型返回空字符串。 

| 节点类型 | 名称 |
| --- | --- |
| [Attribute](../../../system/attribute/)| 属性的名称。 |
| DocumentType| 文档类型名称。 |
| Element| 标签名称。 |
| EntityReference| 被引用实体的名称。 |
| ProcessingInstruction| 处理指令的目标。 |
| [XmlDeclaration](../../xmldeclaration/)| 文字字符串 `xml`。 |


## See Also

* 类 [String](../../../system/string/)
* 类 [XmlNodeReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)