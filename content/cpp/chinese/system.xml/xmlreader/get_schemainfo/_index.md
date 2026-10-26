---
title: get_SchemaInfo()
second_title: Aspose.Slides for C++ API 参考
description: 返回已分配给当前节点的模式信息，该信息是模式验证的结果。
type: docs
weight: 196
url: /zh/system.xml/xmlreader/get_schemainfo/
---
## XmlReader::get_SchemaInfo() 方法

返回已分配给当前节点的模式信息，该信息是模式验证的结果。

```cpp
virtual SharedPtr<Schema::IXmlSchemaInfo> System::Xml::XmlReader::get_SchemaInfo()
```

### 返回值

一个 IXmlSchemaInfo 对象，其中包含当前节点的模式信息。[Schema](../../../system.xml.schema/) 信息可以在元素、属性或具有非空 [XmlReader::get_ValueType](../get_valuetype/) 值的文本节点上设置。如果当前节点不是上述节点类型之一，或 [XmlReader](../) 实例未报告模式信息，此方法返回 **nullptr**。如果此方法从 [XmlTextReader](../../xmltextreader/) 或 [XmlValidatingReader](../../xmlvalidatingreader/) 对象调用，此方法始终返回 **nullptr**。这些 [XmlReader](../) 实现不通过 get_SchemaInfo 方法公开模式信息。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IXmlSchemaInfo](../../../system.xml.schema/ixmlschemainfo/)
* 类 [XmlReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)