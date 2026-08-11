---
title: get_ValidationFlags()
second_title: Aspose.Slides برای C++ مرجع API
description: "مقداری را برمی‌گرداند که تنظیمات اعتبارسنجی طرح‌واره را نشان می‌دهد. این تنظیم برای اشیاء XmlReader که طرح‌واره‌ها را اعتبارسنجی می‌کنند (مقدار XmlReaderSettings::get_ValidationType برابر با ValidationType::Schema است)."
type: docs
weight: 378
url: /fa/system.xml/xmlreadersettings/get_validationflags/
---
## XmlReaderSettings::get_ValidationFlags() متد

یک مقدار را برمی‌گرداند که تنظیمات اعتبارسنجی طرح‌واره را نشان می‌دهد. این تنظیم برای اشیاء [XmlReader](../../xmlreader/) که طرح‌واره‌ها را اعتبارسنجی می‌کنند (مقدار [XmlReaderSettings::get_ValidationType](../get_validationtype/) برابر با [ValidationType::Schema](../../validationtype/) است).

```cpp
Schema::XmlSchemaValidationFlags System::Xml::XmlReaderSettings::get_ValidationFlags()
```

### مقدار بازگشت

ترکیبی بیتی از مقادیر enumeration که گزینه‌های اعتبارسنجی را مشخص می‌کند. XmlSchemaValidationFlags::ProcessIdentityConstraints و XmlSchemaValidationFlags::AllowXmlAttributes به‌صورت پیش‌فرض فعال هستند. XmlSchemaValidationFlags::ProcessInlineSchema، XmlSchemaValidationFlags::ProcessSchemaLocation و XmlSchemaValidationFlags::ReportValidationWarnings به‌صورت پیش‌فرض غیرفعال هستند.

## انظر به

* Enum [XmlSchemaValidationFlags](../../../system.xml.schema/xmlschemavalidationflags/)
* کلاس [XmlReaderSettings](../)
* فضای نام [System::Xml](../../)
* Library [Aspose.Slides](../../../)