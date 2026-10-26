---
title: XmlSchemaValidationFlags
second_title: Aspose.Slides برای مرجع API C++
description: گزینه‌های اعتبارسنجی طرح‌واره را که توسط کلاس‌های XmlSchemaValidator و XmlReader استفاده می‌شوند، مشخص می‌کند.
type: docs
weight: 1054
url: /fa/system.xml.schema/xmlschemavalidationflags/
---
## XmlSchemaValidationFlags enum

Specifies schema validation options used by the [XmlSchemaValidator](../xmlschemavalidator/) and [XmlReader](../../system.xml/xmlreader/) classes.

```cpp
enum class XmlSchemaValidationFlags
```

### مقدارها

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | پردازش محدودیت‌های هویت، طرح‌واره‌های توکار، راهنمای مکان طرح‌واره یا گزارش هشدارهای اعتبارسنجی طرح‌واره انجام نشود. |
| ProcessInlineSchema | 1 | پردازش طرح‌واره‌های توکار که در طول اعتبارسنجی مواجه می‌شوند. |
| ProcessSchemaLocation | 2 | پردازش راهنمای مکان طرح‌واره (**xsi:schemaLocation**, **xsi:noNamespaceSchemaLocation**) که در طول اعتبارسنجی مواجه می‌شوند. |
| ReportValidationWarnings | 4 | گزارش هشدارهای اعتبارسنجی طرح‌واره که در طول اعتبارسنجی مواجه می‌شوند. |
| ProcessIdentityConstraints | 8 | پردازش محدودیت‌های هویت (**xs:ID**, **xs:IDREF**, **xs:key**, **xs:keyref**, **xs:unique**) که در طول اعتبارسنجی مواجه می‌شوند. |
| AllowXmlAttributes | 16 | اجازهٔ ویژگی‌های xml:* حتی اگر در طرح‌واره تعریف نشده باشند. این ویژگی‌ها بر اساس نوع داده آن‌ها اعتبارسنجی می‌شوند. |

## موارد مرتبط

* Namespace [System::Xml::Schema](../)
* Library [Aspose.Slides](../../)