---
title: WriteAllText()
second_title: Aspose.Slides برای C++ مرجع API
description: یک فایل متنی جدید ایجاد می‌کند یا فایل موجود را بازنویسی می‌نماید و محتویات رشتهٔ مشخص‌شده را با استفاده از رمزگذاری تعیین‌شده در آن می‌نویسد.
type: docs
weight: 469
url: /fa/system.io/file/writealltext/
---
## File::WriteAllText(const String\&, const String\&, const EncodingPtr\&) متد

یک فایل متنی جدید ایجاد می‌کند یا فایل موجود را بازنویسی می‌نماید و محتویات رشتهٔ مشخص‌شده را با استفاده از رمزگذاری مشخص‌شده در آن می‌نویسد.

```cpp
static void System::IO::File::WriteAllText(const String &path, const String &contents, const EncodingPtr &encoding=Text::Encoding::get_UTF8Unmarked())
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | فایلی که باید ایجاد یا بازنویسی شود |
| contents | const [String](../../../system/string/)\& | یک آرایهٔ رشته‌ای |
| encoding | const [EncodingPtr](../../../system/encodingptr/)\& | رمزگذاری کاراکتری که باید استفاده شود |

## موارد مرتبط

* تعریف نوع [EncodingPtr](../../../system/encodingptr/)
* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)