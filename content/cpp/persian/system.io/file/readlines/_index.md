---
title: ReadLines()
second_title: مرجع API Aspose.Slides برای C++
description: محتوای فایل متنی مشخص‌شده را به‌صورت خط به‌خط با استفاده از رمزگذاری کاراکتر مشخص‌شده می‌خواند و مجموعه‌ای قابل شمارش از رشته‌ها را برمی‌گرداند که هر یک نمایانگر یک خط از محتوای فایل هستند.
type: docs
weight: 326
url: /fa/system.io/file/readlines/
---
## File::ReadLines(const String\&, const EncodingPtr\&) متد


محتوای فایل متنی مشخص‌شده را به‌صورت خط به‌خط با استفاده از رمزگذاری کاراکتری که تعیین شده می‌خواند و مجموعه‌ای قابل شمارش از رشته‌ها برمی‌گرداند که هریک نمایانگر یک خط از محتوای فایل هستند.

```cpp
static SharedPtr<Collections::Generic::IEnumerable<String>> System::IO::File::ReadLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایل برای خواندن |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتر برای استفاده |

### مقدار بازگشتی

یک مجموعه قابل شمارش از رشته‌ها که محتوای فایل مشخص‌شده را نشان می‌دهند

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)