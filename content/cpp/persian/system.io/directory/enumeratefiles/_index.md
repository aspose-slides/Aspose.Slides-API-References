---
title: EnumerateFiles()
second_title: مرجع API Aspose.Slides برای C++
description: جستجو برای فایل‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در دایرکتوری مشخص شده و چه در کل درخت دایرکتوری که از آن ریشه می‌گیرد.
type: docs
weight: 40
url: /fa/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) متد

جستجو برای فایل‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در دایرکتوری مشخص‌شده و چه در کل درخت دایرکتوری که از آن ریشه می‌گیرد.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی به دایرکتوری برای جستجو |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها برای جستجو |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو باید فقط در دایرکتوری مشخص شده انجام شود یا در کل درخت دایرکتوری که در دایرکتوری مشخص شده ریشه دارد |

### مقدار بازگشتی

مجموعه قابل شمارشی از مسیرهای کامل فایل‌های یافت‌شده که نام آن‌ها با **searchPattern** مطابقت دارد

## موارد مرتبط

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)