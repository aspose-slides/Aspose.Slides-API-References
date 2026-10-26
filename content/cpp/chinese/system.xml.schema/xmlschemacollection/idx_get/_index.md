---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 返回与给定命名空间 URI 关联的 XmlSchema。
type: docs
weight: 53
url: /zh/system.xml.schema/xmlschemacollection/idx_get/
---
## XmlSchemaCollection::idx_get(const String\&) method

返回与给定命名空间 URI 关联的 [XmlSchema](../../xmlschema/)。

```cpp
SharedPtr<XmlSchema> System::Xml::Schema::XmlSchemaCollection::idx_get(const String &ns)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| ns | const [String](../../../system/string/)\& | 要返回的模式关联的命名空间 URI。通常是模式的 **targetNamespace**。 |

### 返回值

与命名空间 URI 关联的 [XmlSchema](../../xmlschema/)；如果没有加载与给定命名空间关联的模式，或命名空间关联的是 XDR 模式，则为 **nullptr**。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [XmlSchema](../../xmlschema/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaCollection](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)