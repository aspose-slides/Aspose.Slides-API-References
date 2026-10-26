---
title: GetUnspecifiedDefaultAttributes()
second_title: مرجع API Aspose.Slides برای C++
description: "قیدهای هویت را بر روی ویژگی‌های پیش‌فرض اعتبارسنجی می‌کند و List مشخص‌شده را با اشیاء XmlSchemaAttribute برای هر ویژگی که مقادیر پیش‌فرض دارد و پیش از این با متد XmlSchemaValidator::ValidateAttribute در زمینه عنصر اعتبارسنجی نشده است، پر می‌کند."
type: docs
weight: 157
url: /fa/system.xml.schema/xmlschemavalidator/getunspecifieddefaultattributes/
---
## XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr\<Collections::Generic::List\<SharedPtr\<Object\>\>\>\&) متد

قیدهای هویت را بر روی ویژگی‌های پیش‌فرض اعتبارسنجی می‌کند و List را با اشیاء [XmlSchemaAttribute](../../xmlschemaattribute/) برای هر ویژگی که مقادیر پیش‌فرض دارد و پیش از آن با متد [XmlSchemaValidator::ValidateAttribute](../validateattribute/) در زمینه عنصر اعتبارسنجی نشده است، پر می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaValidator::GetUnspecifiedDefaultAttributes(const SharedPtr<Collections::Generic::List<SharedPtr<Object>>> &defaultAttributes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| defaultAttributes | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::List](../../../system.collections.generic/list/)\<[SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\>\>\& | یک List برای پر کردن با اشیاء [XmlSchemaAttribute](../../xmlschemaattribute/) برای هر ویژگی که هنوز در طول اعتبارسنجی در زمینه عنصر مورد بررسی قرار نگرفته است. |

## همچنین ببینید

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [List](../../../system.collections.generic/list/)
* کلاس [Object](../../../system/object/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)