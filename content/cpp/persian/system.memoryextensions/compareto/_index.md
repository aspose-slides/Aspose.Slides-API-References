---
title: CompareTo()
second_title: مرجع API Aspose.Slides برای C++
description: دو بازهٔ کاراکتر را با قوانین مقایسهٔ رشته‌ای مشخص مقایسه می‌کند.
type: docs
weight: 404
url: /fa/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) تابع

دو بازهٔ کاراکتر را با قوانین مقایسهٔ رشته‌ای مشخص مقایسه می‌کند.

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### پارامترها

| Parameter | Type | Description |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | اولین بازهٔ کاراکتر |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | دومین بازهٔ کاراکتر |
| comparisonType | [StringComparison](../../system/stringcomparison/) | نوع مقایسهٔ رشته‌ای که باید اعمال شود |

### مقدار بازگشت

مقدار منفی اگر span < other، صفر اگر برابر باشند، مقدار مثبت اگر span > other

## موارد مرتبط

* Enum [StringComparison](../../system/stringcomparison/)
* کلاس [ReadOnlySpan](../../system/readonlyspan/)
* فضای‌نام [System::MemoryExtensions](../)
* کتابخانه [Aspose.Slides](../../)