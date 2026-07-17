---
title: get_SchemaType()
second_title: Aspose.Slides for C++ API 参考
description: 返回一个模式类型对象。
type: docs
weight: 287
url: /zh/system.xml/xmlvalidatingreader/get_schematype/
---
## XmlValidatingReader::get_SchemaType() 方法

返回一个模式类型对象。

```cpp
SharedPtr<Object> System::Xml::XmlValidatingReader::get_SchemaType()
```

### 返回值

XmlSchemaDatatype、XmlSchemaSimpleType 或 XmlSchemaComplexType，取决于节点值是内置 XML [Schema](../../../system.xml.schema/) 定义语言（XSD）类型还是用户定义的 simpleType 或 complexType；**nullptr** 如果当前节点没有模式类型。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [XmlValidatingReader](../)
* 命名空间 [System::Xml](../../)
* 库 [Aspose.Slides](../../../)