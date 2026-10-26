---
title: ToLower()
second_title: Aspose.Slides برای مرجع API C++
description: حروف را با استفاده از فرهنگ مشخص به حروف کوچک تبدیل می‌کند.
type: docs
weight: 443
url: /fa/system.memoryextensions/tolower/
---
## System::MemoryExtensions::ToLower(const ReadOnlySpan\<char16_t\>\&, Span\<char16_t\>\&, const SharedPtr\<Globalization::CultureInfo\>\&) تابع

حروف را با استفاده از فرهنگ مشخص به حروف کوچک تبدیل می‌کند.

```cpp
int32_t System::MemoryExtensions::ToLower(const ReadOnlySpan<char16_t> &source, Span<char16_t> &destination, const SharedPtr<Globalization::CultureInfo> &culture)
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | بازهٔ حروف منبع برای تبدیل |
| destination | [Span](../../system/span/)\<char16_t\>\& | بازهٔ مقصد برای ذخیرهٔ حروف تبدیل‌شده |
| culture | const [SharedPtr](../../system/sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\& | فرهنگی که برای تبدیل استفاده می‌شود (nullptr برای فرهنگ جاری) |

### مقدار بازگشت

تعداد حروف تبدیل‌شده، یا -1 اگر مقصد بیش از حد کوچک باشد

## همچنین ببینید

* تعریف نوع [SharedPtr](../../system/sharedptr/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* کلاس [Span](../../system/span/)
* کلاس [CultureInfo](../../system.globalization/cultureinfo/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)