---
title: ToUpper()
second_title: مرجع API Aspose.Slides برای C++
description: حروف را با استفاده از فرهنگ مشخص به حروف بزرگ تبدیل می‌کند.
type: docs
weight: 469
url: /fa/system.memoryextensions/toupper/
---
## System::MemoryExtensions::ToUpper(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) تابع


حروف را با استفاده از فرهنگ مشخص به حروف بزرگ تبدیل می‌کند.

```cpp
int32_t System::MemoryExtensions::ToUpper(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | بخش کاراکتر منبع برای تبدیل |
| destination | [Span](../../system/span/)\<char16_t\>\& | بخش مقصد برای ذخیره‌سازی کاراکترهای تبدیل‌شده |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | فرهنگی که برای تبدیل استفاده می‌شود (nullptr برای فرهنگ فعلی) |

### مقدار بازگشتی

تعداد کاراکترهای تبدیل‌شده، یا -1 اگر مقصد خیلی کوچک باشد

## موارد مرتبط

* تعریف‌نوع [SharedPtr](../../system/sharedptr/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* کلاس [CultureInfo](../../system.globalization/cultureinfo/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)