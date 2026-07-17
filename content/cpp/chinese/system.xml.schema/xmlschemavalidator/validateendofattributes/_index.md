---
title: ValidateEndOfAttributes()
second_title: Aspose.Slides for C++ API 参考
description: 验证元素上下文中是否存在所有必需属性，并准备 XmlSchemaValidator 对象以验证该元素的子内容。
type: docs
weight: 170
url: /zh/system.xml.schema/xmlschemavalidator/validateendofattributes/
---
## XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr\<XmlSchemaInfo\>\&) 方法

验证元素上下文中是否存在所有必需属性，并准备 [XmlSchemaValidator](../) 对象以验证该元素的子内容。

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateEndOfAttributes(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | 一个 [XmlSchemaInfo](../../xmlschemainfo/) 对象，其属性在成功验证元素上下文中所有必需属性均已存在后被设置。此参数可以为 **nullptr**。 |

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlSchemaInfo](../../xmlschemainfo/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)