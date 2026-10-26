---
title: GetCultureInfo()
second_title: مرجع API Aspose.Slides برای C++
description: فرهنگ را بر اساس نام آن دریافت می‌کند. مشابه CreateSpecificCulture.
type: docs
weight: 586
url: /fa/system.globalization/cultureinfo/getcultureinfo/
---
## CultureInfo::GetCultureInfo(const String\&) متد

فرهنگ را بر اساس نام آن دریافت می‌کند. مشابه CreateSpecificCulture.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام پیش‌تعریف شدهٔ فرهنگ یا نام شیء فرهنگ موجود. |

### مقدار بازگشت

شیء فرهنگ تازه ساخته شده.

## CultureInfo::GetCultureInfo(const String\&, const String\&) متد

فرهنگ را بر اساس نام آن دریافت می‌کند.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(const String &name, const String &text_and_compare_culture_name)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | نام فرهنگ. |
| text_and_compare_culture_name | const [String](../../../system/string/)\& | نام فرهنگی که برای اشیاء [TextInfo](../../textinfo/) و [CompareInfo](../../compareinfo/) استفاده می‌شود. |

### مقدار بازگشت

شیء فرهنگ.

## CultureInfo::GetCultureInfo(int32_t) متد

فرهنگ را بر اساس شناسه دریافت می‌کند.

```cpp
static CultureInfoPtr System::Globalization::CultureInfo::GetCultureInfo(int32_t culture)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| culture | **int32_t** | شناسهٔ فرهنگ. |

### مقدار بازگشت

شیء فرهنگ تازه ساخته شده.

## مراجع

* Typedef [CultureInfoPtr](../../cultureinfoptr/)
* Class [String](../../../system/string/)
* Class [CultureInfo](../)
* Namespace [System::Globalization](../../)
* Library [Aspose.Slides](../../../)