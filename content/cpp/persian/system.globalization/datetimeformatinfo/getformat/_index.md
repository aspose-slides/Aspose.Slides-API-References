---
title: GetFormat()
second_title: Aspose.Slides برای مرجع API C++
description: فرمت‌کنندهٔ نوع خاص را دریافت می‌کند.
type: docs
weight: 14
url: /fa/system.globalization/datetimeformatinfo/getformat/
---
## DateTimeFormatInfo::GetFormat(const TypeInfo\&) method

Formatter را از نوع خاص دریافت می‌کند.

```cpp
SharedPtr<Object> System::Globalization::DateTimeFormatInfo::GetFormat(const TypeInfo &format_type) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| format_type | const [TypeInfo](../../../system/typeinfo/)\& | نوع فورمتری که باید دریافت شود؛ فقط نوع [DateTimeFormatInfo](../) پشتیبانی می‌شود. |

### مقدار برگشت

Formatter یا null اگر در دسترس نباشد.

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Object](../../../system/object/)
* کلاس [TypeInfo](../../../system/typeinfo/)
* کلاس [DateTimeFormatInfo](../)
* فضای نام [System::Globalization](../../)
* کتابخانه [Aspose.Slides](../../../)