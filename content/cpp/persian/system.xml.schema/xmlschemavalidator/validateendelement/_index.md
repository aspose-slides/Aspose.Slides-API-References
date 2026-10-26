---
title: ValidateEndElement()
second_title: Aspose.Slides برای C++ مرجع API
description: متن محتوای عنصر را بر اساس نوع دادهٔ آن برای عناصری با محتوای ساده اعتبارسنجی می‌کند و محتوای عنصر فعلی را برای عناصری با محتوای پیچیده کامل می‌سنجد.
type: docs
weight: 209
url: /fa/system.xml.schema/xmlschemavalidator/validateendelement/
---
## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&) method

بررسی می‌کند که آیا محتوای متنی عنصر بر حسب نوع دادهٔ آن برای عناصری با محتوای ساده معتبر است و بررسی می‌کند که آیا محتوای عنصر فعلی برای عناصری با محتوای پیچیده کامل است.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که ویژگی‌های آن پس از اعتبارسنجی موفق عنصر تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |

### مقدار بازگشت

مقدار متنی تجزیه‌شده و تایپ‌شدهٔ عنصر در صورتی که عنصر محتوای ساده داشته باشد.

## XmlSchemaValidator::ValidateEndElement(const SharedPtr\<XmlSchemaInfo\>\&, const SharedPtr\<Object\>\&) method

بررسی می‌کند که آیا محتوای متنی عنصر مشخص شده بر حسب نوع دادهٔ آن معتبر است.

```cpp
SharedPtr<Object> System::Xml::Schema::XmlSchemaValidator::ValidateEndElement(const SharedPtr<XmlSchemaInfo> &schemaInfo, const SharedPtr<Object> &typedValue)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| schemaInfo | const [SharedPtr](../../../system/sharedptr/)\<[XmlSchemaInfo](../../xmlschemainfo/)\>\& | یک شیء [XmlSchemaInfo](../../xmlschemainfo/) که ویژگی‌های آن پس از اعتبارسنجی موفق محتوای متنی عنصر تنظیم می‌شود. این پارامتر می‌تواند **nullptr** باشد. |
| typedValue | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | محتوای متنی تایپ‌شدهٔ عنصر. |

### مقدار بازگشت

محتوای سادهٔ تجزیه‌شده و تایپ‌شدهٔ عنصر.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [XmlSchemaInfo](../../xmlschemainfo/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* Library [Aspose.Slides](../../../)