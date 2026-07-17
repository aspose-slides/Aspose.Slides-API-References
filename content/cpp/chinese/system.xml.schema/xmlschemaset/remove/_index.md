---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从 XmlSchemaSet 中删除指定的 XML Schema 定义语言 (XSD) 架构。
type: docs
weight: 170
url: /zh/system.xml.schema/xmlschemaset/remove/
---
## XmlSchemaSet::Remove(const SharedPtr\<XmlSchema\>\&) 方法

从 [XmlSchemaSet](../) 中删除指定的 XML [Schema](../../) 定义语言 (XSD) 架构。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Remove(const SharedPtr<XmlSchema> &schema)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\>\& | 要从 [XmlSchemaSet](../) 中删除的 [XmlSchema](../../xmlschema/) 对象。 |

### 返回值

已从 [XmlSchemaSet](../) 中删除的 [XmlSchema](../../xmlschema/) 对象，若在 [XmlSchemaSet](../) 中未找到该架构，则返回 **nullptr**。

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchema](../../xmlschema/)
* 类 [XmlSchemaSet](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)