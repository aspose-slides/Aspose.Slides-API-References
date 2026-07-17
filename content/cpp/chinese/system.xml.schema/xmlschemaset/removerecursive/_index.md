---
title: RemoveRecursive()
second_title: Aspose.Slides for C++ API 参考
description: 从 XmlSchemaSet 移除指定的 XML Schema 定义语言（XSD）模式以及它导入的所有模式。
type: docs
weight: 183
url: /zh/system.xml.schema/xmlschemaset/removerecursive/
---
## XmlSchemaSet::RemoveRecursive(const SharedPtr\<XmlSchema\>\&) method

移除指定的 XML [Schema](../../) 定义语言（XSD）模式以及它从 [XmlSchemaSet](../) 导入的所有模式。

```cpp
bool System::Xml::Schema::XmlSchemaSet::RemoveRecursive(const SharedPtr<XmlSchema> &schemaToRemove)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schemaToRemove | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要从 [XmlSchemaSet](../) 中移除的 [XmlSchema](../../xmlschema/) 对象。 |

### 返回值

**true** 如果成功移除 [XmlSchema](../../xmlschema/) 对象及其所有导入；否则，**false**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchema](../../xmlschema/)
* 类 [XmlSchemaSet](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)