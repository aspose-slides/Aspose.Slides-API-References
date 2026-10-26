---
title: Copy()
second_title: مرجع API Aspose.Slides برای C++
description: فایل مشخص شده را به مکان مشخص شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، یک پارامتر مشخص می‌کند که آیا باید بازنویسی شود یا نه.
type: docs
weight: 40
url: /fa/system.io/file/copy/
---
## File::Copy(const String\&, const String\&, bool) متد


فایل مشخص شده را به مکان مشخص شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، یک پارامتر مشخص می‌کند که آیا باید بازنویسی شود یا نه.

```cpp
static void System::IO::File::Copy(const String &sourceFileName, const String &destFileName, bool overwrite=false)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | مسیر فایلی که باید کپی شود |
| destFileName | const [String](../../../system/string/)\& | مسیر مکان جدید فایلی که باید کپی شود |
| overwrite | **bool** | True اگر فایل مقصد موجود باید بازنویسی شود، false اگر در صورت وجود قبلاً فایل هدف کپی باید شکست بخورد |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [File](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)