---
title: DtdProcessing
second_title: Aspose.Slides برای C++ مرجع API
description: گزینه‌های پردازش DTDها را مشخص می‌کند. شمارنده DtdProcessing توسط کلاس XmlReaderSettings استفاده می‌شود.
type: docs
weight: 638
url: /fa/system.xml/dtdprocessing/
---
## DtdProcessing enum

گزینه‌های پردازش DTDها را مشخص می‌کند. شمارنده DtdProcessing توسط کلاس [XmlReaderSettings](../xmlreadersettings/) استفاده می‌شود.

```cpp
enum class DtdProcessing
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Prohibit | 0 | مشخص می‌کند که هنگامی که یک DTD مواجه می‌شود، یک XmlException پرتاب می‌شود با پیامی که می‌گوید DTDها ممنوع هستند. این رفتار پیش‌فرض است. |
| Ignore | 1 | باعث می‌شود عنصر DOCTYPE نادیده گرفته شود. هیچ پردازشی برای DTD انجام نمی‌شود و DTD/DOCTYPE در خروجی از دست می‌رود. |
| Parse | 2 | برای تجزیه DTDها استفاده می‌شود. |

## موارد مرتبط

* فضای نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)