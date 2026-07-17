---
title: ValidateAttribute()
second_title: Aspose.Slides C++ API 参考
description: 在当前元素上下文中验证属性名称、命名空间 URI 和属性值。
type: docs
weight: 144
url: /zh/system.xml.schema/xmlschemavalidator/validateattribute/
---
## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, const String\&, const SharedPtr\<XmlSchemaInfo\>\&) 方法

验证当前元素上下文中的属性名称、命名空间 URI 和属性值。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, const String &attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要验证的属性的本地名称。 |
| namespaceUri | const [String](../../../system/string/)\& | 要验证的属性的命名空间 URI。 |
| attributeValue | const [String](../../../system/string/)\& | 要验证的属性的值。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 在成功验证属性后其属性被设置的[XmlSchemaInfo](../../xmlschemainfo/)对象。此参数可以为 **nullptr**。 |

### 返回值

已验证的属性的值。

## XmlSchemaValidator::ValidateAttribute(const String\&, const String\&, XmlValueGetter, const SharedPtr\<XmlSchemaInfo\>\&) 方法

验证当前元素上下文中的属性名称、命名空间 URI 和属性值。

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateAttribute(const String &localName, const String &namespaceUri, XmlValueGetter attributeValue, const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| localName | const [String](../../../system/string/)\& | 要验证的属性的本地名称。 |
| namespaceUri | const [String](../../../system/string/)\& | 要验证的属性的命名空间 URI。 |
| attributeValue | [XmlValueGetter](../../xmlvaluegetter/) | 用于将属性的值以兼容属性的 XML [Schema](../../) 定义语言 (XSD) 类型的类型传递的 XmlValueGetter 回调。 |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 在成功验证属性后其属性被设置的[XmlSchemaInfo](../../xmlschemainfo/)对象。此参数可以为 **nullptr**。 |

### 返回值

已验证的属性的值。

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [XmlValueGetter](../../xmlvaluegetter/)
* 类 [Object](../../../system/object/)
* 类 [String](../../../system/string/)
* 类 [XmlSchemaInfo](../../xmlschemainfo/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)