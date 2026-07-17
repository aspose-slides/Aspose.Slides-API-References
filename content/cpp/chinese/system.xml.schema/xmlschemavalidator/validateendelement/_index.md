---
title: ValidateEndElement()
second_title: Aspose.Slides for C++ API 参考
description: 验证具有简单内容的元素的文本内容是否符合其数据类型的要求，并验证具有复杂内容的元素的当前内容是否完整。
type: docs
weight: 209
url: /zh/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method

验证具有简单内容的元素的文本内容是否符合其数据类型的要求，并验证具有复杂内容的元素的当前内容是否完整。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一个在成功验证元素后其属性被设置的 [XmlSchemaInfo](../../xmlschemainfo/) 对象。此参数可以是 **nullptr**。 |

### 返回值

如果元素具有简单内容，则返回该元素的已解析、已类型化的文本值。

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method

验证指定元素的文本内容是否符合其数据类型的要求。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一个在成功验证元素的文本内容后其属性被设置的 [XmlSchemaInfo](../../xmlschemainfo/) 对象。此参数可以是 **nullptr**。 |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 元素的已类型化文本内容。 |

### 返回值

元素的已解析、已类型化的简单内容。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Object](../../../system/object/)
* 类 [XmlSchemaInfo](../../xmlschemainfo/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)