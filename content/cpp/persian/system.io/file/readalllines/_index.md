---
title: ReadAllLines()
second_title: مرجع API Aspose.Slides برای C++
description: محتویات فایل متنی مشخص شده را به صورت خط به خط به یک آرایه‌ای از رشته‌ها می‌خواند و با استفاده از رمزگذاری کاراکتر مشخص شده.
type: docs
weight: 300
url: /fa/system.io/file/readalllines/
---
## File::ReadAllLines(const String\&, const EncodingPtr\&) متد

محتوای فایل متنی مشخص شده را به صورت خط به خط به یک آرایه‌ای از رشته‌ها می‌خواند و با استفاده از رمزگذاری کاراکتر مشخص شده.

```cpp
static ArrayPtr<String> System::IO::File::ReadAllLines(const String &path, const EncodingPtr &encoding=Text::Encoding::get_UTF8())
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر فایلی که باید خوانده شود |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتری که باید استفاده شود |

### مقدار برگشتی

یک آرایهٔ رشته‌ای که هر عنصر آن نمایانگر یک خط منفرد از فایل مشخص شده است

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [EncodingPtr](../../../system/encodingptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)