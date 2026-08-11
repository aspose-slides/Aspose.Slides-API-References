---
title: EnumerateFileSystemEntries()
second_title: مرجع API برای Aspose.Slides در C++
description: فایل‌ها و دایرکتوری‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، یا در دایرکتوری مشخص‌شده یا در کل درخت دایرکتوری که ریشه‌اش در آن دایرکتوری است، جستجو می‌کند.
type: docs
weight: 53
url: /fa/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) متد

فایل‌ها و دایرکتوری‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، یا در دایرکتوری مشخص‌شده یا در کل درخت دایرکتوری که ریشهٔ آن در دایرکتوری مشخص‌شده است جستجو می‌کند.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### آرگومان‌ها

| پارامتر | نوع | توضحیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی دایرکتوری که قرار است جستجو انجام شود |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و دایرکتوری‌هایی که جستجو می‌شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که جستجو فقط در دایرکتوری مشخص‌شده انجام شود یا در کل درخت دایرکتوری ریشه‌دار در آن |

### مقدار بازگشت

مجموعهٔ قابل شمارش از مسیرهای کامل فایل‌ها و دایرکتوری‌های پیدا شده که نام‌هایشان با **searchPattern** مطابقت دارد

## مشاهده کنید

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* کلاس [String](../../../system/string/)
* کلاس [Directory](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)