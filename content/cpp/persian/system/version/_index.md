---
title: Version
second_title: مرجع API Aspose.Slides برای C++
description: "یک شماره نسخه را نمایش می‌دهد. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس System::SmartPtr برای مدیریت اشیاء این نوع استفاده نکنید."
type: docs
weight: 1470
url: /fa/system/version/
---
## کلاس Version

یک شماره نسخه را نمایش می‌دهد. این نوع باید روی پشته تخصیص داده شود و به توابع به صورت مقدار یا مرجع پاس داده شود. هرگز از کلاس [System::SmartPtr](../smartptr/) برای مدیریت اشیاء این نوع استفاده نکنید.

```cpp
class Version
```

## متدها

| متد | توضیح |
| --- | --- |
| int [CompareTo](./compareto/)(const [Version](./)\&) const | نسخه‌های نمایانده شده توسط شیء جاری و شیء مشخص‌شده را مقایسه می‌کند. |
| **bool** [Equals](./equals/)(const [Version](./)\&) const | تشخیص می‌دهد که آیا شماره نسخه‌های نمایانده شده توسط شیء جاری و شیء مشخص‌شده برابر هستند یا نه. |
| int [get_Build](./get_build/)() const | شماره ساخت را برمی‌گرداند. |
| int [get_Major](./get_major/)() const | نسخه اصلی را برمی‌گرداند. |
| **int16_t** [get_MajorRevision](./get_majorrevision/)() const | مقدار 16 بیتی بالایی شماره بازنگری را برمی‌گرداند. |
| int [get_Minor](./get_minor/)() const | نسخه فرعی را برمی‌گرداند. |
| **int16_t** [get_MinorRevision](./get_minorrevision/)() const | مقدار 16 بیتی پایینی شماره بازنگری را برمی‌گرداند. |
| int [get_Revision](./get_revision/)() const | شماره بازنگری را برمی‌گرداند. |
| int [GetHashCode](./gethashcode/)() const | کد هش برای شیء جاری را برمی‌گرداند. |
| static [Version](./) [Parse](./parse/)(const [String](../string/)\&) | نمایش رشته‌ای یک شماره نسخه را به یک نمونه معادل از کلاس [Version](./) تبدیل می‌کند. |
| [String](../string/) [ToString](./tostring/)() const | نمایش رشته‌ای شماره نسخه نمایانده شده توسط شیء جاری را برمی‌گرداند. |
| [String](../string/) [ToString](./tostring/)(int) const | نمایش رشته‌ای تعداد بخش‌های مشخص‌شده از شماره نسخه نمایانده شده توسط شیء جاری را برمی‌گرداند. |
|  [Version](./version/)(int, int, int, int) | نمونه‌ای می‌سازد که مقادیر major، minor، build و revision مشخص‌شده را نمایانده است. |
|  [Version](./version/)(int, int, int) | نمونه‌ای می‌سازد که مقادیر major، minor و build مشخص‌شده را نمایانده است. |
|  [Version](./version/)(int, int) | نمونه‌ای می‌سازد که مقادیر major و مقادیر دیگر را نمایانده است. |
|  [Version](./version/)(const [String](../string/)\&) | نمونه‌ای می‌سازد که شماره نسخه‌ای که به صورت رشته نمایش داده شده را نمایانده است. |
|  [Version](./version/)() | نمونه‌ای می‌سازد که شماره نسخه 0.0.-1.-1 را نمایانده است. |
## موارد مرتبط

* فضای نام [System](../)
* کتابخانه [Aspose.Slides](../../)