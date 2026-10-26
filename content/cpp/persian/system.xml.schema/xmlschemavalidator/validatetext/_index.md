---
title: ValidateText()
second_title: مرجع API Aspose.Slides برای C++
description: بررسی می‌کند که آیا رشته متن مشخص‌شده در زمینه عنصر فعلی مجاز است و اگر عنصر فعلی محتوای ساده داشته باشد، متن را برای اعتبارسنجی جمع‌آوری می‌کند.
type: docs
weight: 183
url: /fa/system.xml.schema/xmlschemavalidator/validatetext/
---
## XmlSchemaValidator::ValidateText(const String\&) متد

بررسی می‌کند که آیا **string** متنی مشخص شده در زمینه عنصر فعلی مجاز است یا خیر، و اگر عنصر فعلی محتوای ساده داشته باشد، متن را برای اعتبارسنجی جمع‌آوری می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(const String &elementValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| elementValue | const [String](../../../system/string/)\& | یک **string** متنی برای اعتبارسنجی در زمینه عنصر فعلی. |

## XmlSchemaValidator::ValidateText(XmlValueGetter) متد

بررسی می‌کند که آیا متنی که توسط شیء XmlValueGetter مشخص‌شده بازگردانده می‌شود در زمینه عنصر فعلی مجاز است یا خیر، و اگر عنصر فعلی محتوای ساده داشته باشد، متن را برای اعتبارسنجی جمع‌آوری می‌کند.

```cpp
void System::Xml::Schema::XmlSchemaValidator::ValidateText(XmlValueGetter elementValue)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| elementValue | [XmlValueGetter](../../xmlvaluegetter/) | یک callback از نوع XmlValueGetter که برای انتقال مقدار متن به‌عنوان نوعی سازگار با زبان تعریف XML [Schema](../../) (XSD) ویژگی استفاده می‌شود. |

## مراجع

* تعریف نوع [XmlValueGetter](../../xmlvaluegetter/)
* کلاس [String](../../../system/string/)
* کلاس [XmlSchemaValidator](../)
* فضای‌نام [System::Xml::Schema](../../)
* کتابخانه [Aspose.Slides](../../../)