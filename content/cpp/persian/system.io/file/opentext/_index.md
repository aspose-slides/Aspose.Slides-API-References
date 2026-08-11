---
title: OpenText()
second_title: مرجع API Aspose.Slides برای C++
description: فایل موجود مشخص شده را برای خواندن متن با استفاده از رمزگذاری UTF-8 و بدون اشتراک باز می‌کند.
type: docs
weight: 261
url: /fa/system.io/file/opentext/
---
## File::OpenText(const String\&, const EncodingPtr\&) متد

فایل موجود مشخص شده را برای خواندن متن با استفاده از رمزگذاری UTF-8 و بدون اشتراک باز می‌کند.

```cpp
static StreamReaderPtr System::IO::File::OpenText(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید باز شود |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتری که باید استفاده شود |

### مقدار بازگشت

یک اشاره‌گر اشتراکی به شیء [StreamWriter](../../streamwriter/) مرتبط با فایل باز شده

## موارد مرتبط

* تعریف نوع [StreamReaderPtr](../../../system/streamreaderptr/)
* تعریف نوع [EncodingPtr](../../../system/encodingptr/)
* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)