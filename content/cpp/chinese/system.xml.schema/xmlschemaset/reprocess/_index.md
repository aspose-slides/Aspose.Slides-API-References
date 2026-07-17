---
title: Reprocess()
second_title: Aspose.Slides for C++ API 参考
description: 重新处理已存在于 XmlSchemaSet 中的 XML Schema 定义语言 (XSD) 架构。
type: docs
weight: 222
url: /zh/system.xml.schema/xmlschemaset/reprocess/
---
## XmlSchemaSet::Reprocess(SharedPtr\<XmlSchema\>) 方法

重新处理已存在于 [XmlSchemaSet](../) 中的 XML [Schema](../../) 定义语言 (XSD) 架构。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaSet::Reprocess(SharedPtr<XmlSchema> schema)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schema | [SharedPtr](../../../system/sharedptr/)\<[XmlSchema](../../xmlschema/)\> | 要重新处理的架构。 |

### 返回值

如果模式是有效模式，则返回 [XmlSchema](../../xmlschema/) 对象。如果模式无效且指定了 ValidationEventHandler，则返回 **nullptr** 并触发相应的验证事件。否则，将抛出 XmlSchemaException。

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchema](../../xmlschema/)
* 类 [XmlSchemaSet](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)