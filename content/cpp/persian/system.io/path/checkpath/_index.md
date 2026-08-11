---
title: CheckPath()
second_title: مرجع API Aspose.Slides برای C++
description: مشخص می‌کند که آیا مسیر مشخص‌شده معتبر است یا نه با بررسی اینکه آیا حاوی کاراکترهای نامعتبر است. اگر مسیر حاوی کاراکترهای نامعتبر باشد، یک استثنا پرتاب می‌شود.
type: docs
weight: 209
url: /fa/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) متد


مشخص می‌کند که آیا مسیر مشخص‌شده معتبر است یا نه با بررسی اینکه آیا حاوی کاراکترهای نامعتبر است. اگر مسیر حاوی کاراکترهای نامعتبر باشد، یک استثنا پرتاب می‌شود.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر برای بررسی |
| msg | const [String](../../../system/string/)\& | پیامی که برای سازندهٔ شی استثنا ارسال می‌شود |
| allow_empty | **bool** | مشخص می‌کند که آیا یک رشتهٔ خالی یا null باید به‌عنوان مسیر صحیح در نظر گرفته شود (true) یا خیر (false)؛ اگر این پارامتر false باشد و **path** خالی باشد، یک ArgumentException پرتاب می‌شود؛ اگر این پارامتر false باشد و **path** null باشد، یک ArgumentNullException پرتاب می‌شود |

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [Path](../)
* فضای نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)