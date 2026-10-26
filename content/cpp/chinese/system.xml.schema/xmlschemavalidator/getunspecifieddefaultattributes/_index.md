---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API 参考
description: "在元素上下文中，使用 XmlSchemaValidator::ValidateAttribute 方法验证默认属性的标识约束，并使用 XmlSchemaAttribute 对象填充指定的 List，以处理那些具有默认值但尚未被验证的属性。"
type: docs
weight: 157
url: /zh/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>>&) 方法

在元素上下文中，验证默认属性的标识约束，并使用 [XmlSchemaAttribute](../../xmlschemaattribute/) 对象填充指定的 List，以便处理那些尚未使用 [XmlSchemaValidator::ValidateAttribute](../validateattribute/) 方法进行验证的具有默认值的属性。

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)<[Collections::Generic::List](../../../system.collections.generic/list/)<[SharedPtr](../../../system/sharedptr/)<[Object](../../../system/object/)>>> & | 用于在元素上下文中验证期间填充 [XmlSchemaAttribute](../../xmlschemaattribute/) 对象的 List，以处理尚未遇到的任何属性。 |

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [List](../../../system.collections.generic/list/)
* 类 [Object](../../../system/object/)
* 类 [XmlSchemaValidator](../)
* 命名空间 [System::Xml::Schema](../../)
* 库 [Aspose.Slides](../../../)