---
title: HasFeature()
second_title: Aspose.Slides برای مرجع API C++
description: آزمون می‌کند که آیا پیاده‌سازی مدل شیء سند (DOM) یک ویژگی خاص را پیاده‌سازی می‌کند.
type: docs
weight: 14
url: /fa/system.xml/xmlimplementation/hasfeature/
---
## XmlImplementation::HasFeature(const String\&, const String\&) متد

تست می‌کند که آیا پیاده‌سازی Document [Object](../../../system/object/) Model (DOM) یک ویژگی خاص را پیاده‌سازی می‌کند.

```cpp
bool System::Xml::XmlImplementation::HasFeature(const String &strFeature, const String &strVersion)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| strFeature | const [String](../../../system/string/)\& | نام بستهٔ ویژگی برای تست. این نام حساس به حروف بزرگ یا کوچک نیست. |
| strVersion | const [String](../../../system/string/)\& | شماره نسخهٔ نام بسته برای تست. اگر نسخه مشخص نشده باشد (**nullptr**)، پشتیبانی از هر نسخه‌ای از ویژگی باعث می‌شود این متد **true** برگرداند. |

### مقدار بازگشت

**true** اگر ویژگی در نسخهٔ مشخص شده پیاده‌سازی شده باشد؛ در غیر این صورت **false**.

## توضیحات

جدول زیر ترکیب‌هایی را نشان می‌دهد که باعث می‌شود **HasFeature** **true** برگرداند.

| strFeature | strVersion |
| --- | --- |
| XML | 1.0 |
| XML | 2.0 |

## مراجع دیگر

* کلاس [String](../../../system/string/)
* کلاس [XmlImplementation](../)
* فضای‌نام [System::Xml](../../)
* کتابخانه [Aspose.Slides](../../../)