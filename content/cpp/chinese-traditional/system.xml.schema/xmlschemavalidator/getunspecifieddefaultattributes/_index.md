---
title: GetUnspecifiedDefaultAttributes()
second_title: Aspose.Slides for C++ API 參考
description: "驗證預設屬性的身份約束，並以 XmlSchemaAttribute 物件填充指定的 List，針對任何在元素上下文中尚未使用 XmlSchemaValidator::ValidateAttribute 方法先前驗證過的預設值屬性。"
type: docs
weight: 157
url: /zh-hant/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) method

驗證預設屬性的身份約束，並以 [XmlSchemaAttribute](../../xmlschemaattribute/) 物件填充指定的 List，針對任何尚未使用 [XmlSchemaValidator::ValidateAttribute](../validateattribute/) 方法在元素上下文中先前驗證過的預設值屬性。

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | 用 [XmlSchemaAttribute](../../xmlschemaattribute/) 物件填充的 List，用於任何在元素上下文驗證期間尚未遇到的屬性。 |

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [List](../../../system.collections.generic/list/)
* Class [Object](../../../system/object/)
* Class [XmlSchemaValidator](../)
* Namespace [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)