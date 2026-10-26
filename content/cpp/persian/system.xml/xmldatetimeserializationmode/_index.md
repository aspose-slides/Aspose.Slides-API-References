---
title: XmlDateTimeSerializationMode
second_title: Aspose.Slides برای C++ مرجع API
description: مشخص می‌کند که هنگام تبدیل بین رشته و DateTime، مقدار زمان چگونه رفتار شود.
type: docs
weight: 781
url: /fa/system.xml/xmldatetimeserializationmode/
---
## XmlDateTimeSerializationMode enum


Specifies how to treat the time value when converting between string and [DateTime](../../system/datetime/).

```cpp
enum class XmlDateTimeSerializationMode
```

### مقادیر

| نام | مقدار | توضیح |
| --- | --- | --- |
| Local | 0 | به عنوان زمان محلی در نظر گرفته می‌شود. اگر شیء [DateTime](../../system/datetime/) نمایانگر زمان هماهنگ جهانی (UTC) باشد، به زمان محلی تبدیل می‌شود. |
| Utc | 1 | به عنوان UTC در نظر گرفته می‌شود. اگر شیء [DateTime](../../system/datetime/) نمایانگر زمان محلی باشد، به یک UTC تبدیل می‌شود. |
| Unspecified | 2 | به عنوان زمان محلی در نظر گرفته می‌شود اگر یک [DateTime](../../system/datetime/) به رشته تبدیل می‌شود. اگر یک رشته به [DateTime](../../system/datetime/) تبدیل می‌شود، در صورت مشخص شدن منطقه زمانی به زمان محلی تبدیل شود. |
| RoundtripKind | 3 | اطلاعات منطقه زمانی باید هنگام تبدیل حفظ شود. |

## همچنین ببینید

* فضای‌نام [System::Xml](../)
* کتابخانه [Aspose.Slides](../../)