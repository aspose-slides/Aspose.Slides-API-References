---
title: ValidationType
second_title: Aspose.Slides برای C++ مرجع API
description: نوع اعتبارسنجی که باید انجام شود را مشخص می‌کند.
type: docs
weight: 729
url: /fa/system.xml/validationtype/
---
## ValidationType enum

نوع اعتبارسنجی که باید انجام شود را مشخص می‌کند.

```cpp
enum class ValidationType
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | هیچ اعتبارسنجی انجام نمی‌شود و هیچ خطای اعتبارسنجی‌ای پرتاب نمی‌شود. این تنظیم یک تجزیه‌کننده غیر اعتبارسنجی سازگار با XML 1.0 ایجاد می‌کند. |
| Auto | 1 | در صورت یافتن اطلاعات DTD یا schema اعتبارسنجی می‌کند. |
| DTD | 2 | بر اساس DTD اعتبارسنجی می‌کند. |
| XDR | 3 | بر اساس طرح‌واره‌های XML-Data Reduced (XDR) اعتبارسنجی می‌کند، از جمله طرح‌واره‌های XDR داخلی. طرح‌واره‌های XDR با استفاده از پیشوند فضای‌نامی **x-schema** یا مقدار [XmlValidatingReader::get_Schemas](../xmlvalidatingreader/get_schemas/) شناسایی می‌شوند. |
| Schema | 4 | بر اساس طرح‌واره‌های زبان تعریف XML [Schema](../../system.xml.schema/) (XSD) اعتبارسنجی می‌کند، از جمله XML Schemas داخلی. XML Schemas با URI‌های فضای‌نامی از طریق ویژگی **schemaLocation** یا **Schemas** ارائه‌شده مرتبط می‌شوند. |

## مراجع

* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)