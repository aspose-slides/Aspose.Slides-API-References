---
title: ToByteArray()
second_title: مرجع API Aspose.Slides برای C++
description: یک رشته یا زیررشته را به آرایه‌ای از بایت‌ها تبدیل می‌کند.
type: docs
weight: 508
url: /fa/system/string/tobytearray/
---
## String::ToByteArray(int32_t, int32_t, bool) const متد

رشته یا زیررشته را به آرایه‌ای از بایت‌ها تبدیل می‌کند.

```cpp
ArrayPtr<uint8_t> System::String::ToByteArray(int32_t startIndex=0, int32_t length=INT32_MAX, bool LE=1) const
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | **int32_t** | اندیس شروع زیررشته. |
| length | **int32_t** | طول زیررشته. |
| LE | **bool** | اگر true باشد، کاراکترها را با little endianness رمزگذاری می‌کند؛ در غیر این صورت از big endianness استفاده می‌کند. |

### مقدار بازگشت

[Array](../../array/) شامل بایت‌هایی که نمایانگر کاراکترهای رشته هستند.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../arrayptr/)
* کلاس [String](../)
* فضای نام [System](../../)
* کتابخانه [Aspose.Slides](../../../)