---
title: XmlSchemaContentProcessing
second_title: مرجع API Aspose.Slides برای C++
description: اطلاعاتی دربارهٔ حالت اعتبارسنجی جایگزینی عناصر any و anyAttribute فراهم می‌کند.
type: docs
weight: 976
url: /fa/system.xml.schema/xmlschemacontentprocessing/
---
## XmlSchemaContentProcessing enum

اطلاعاتی درباره حالت اعتبارسنجی جایگزینی عناصر **any** و **anyAttribute** فراهم می‌کند.

```cpp
enum class XmlSchemaContentProcessing
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| None | 0 | موارد سند اعتبارسنجی نمی‌شوند. |
| Skip | 1 | موارد سند باید شامل XML سالم باشند و توسط طرح‌واره اعتبارسنجی نمی‌شوند. |
| Lax | 2 | اگر طرح‌واره مرتبط پیدا شود، موارد سند اعتبارسنجی می‌شوند. در غیر این صورت خطایی رخ نخواهد داد. |
| Strict | 3 | پردازشگر طرح‌واره باید طرح‌واره‌ای مرتبط با فضای نام مشخص شده را پیدا کند تا موارد سند را اعتبارسنجی کند. |

## مراجع

* فضای‌نام [System::Xml::Schema](../)
* کتابخانه [Aspose.Slides](../../)