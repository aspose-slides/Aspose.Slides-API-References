---
title: EnumerateDirectories()
second_title: Aspose.Slides برای C++ مرجع API
description: دایرکتوری‌هایی را که معیارهای جستجوی مشخص را برآورده می‌کنند، چه در دایرکتوری مشخص شده و چه در کل درخت دایرکتوری ریشه‌دار در آن دایرکتوری، جستجو می‌کند.
type: docs
weight: 27
url: /fa/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String&, const String&, SearchOption) متد

Searches for the directories that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی دایرکتوری که در آن جستجو انجام می‌شود |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام دایرکتوری‌هایی که جستجو می‌شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو فقط در دایرکتوری مشخص باید انجام شود یا در کل درخت دایرکتوری ریشه‌دار در دایرکتوری مشخص |

### مقدار بازگشت

مجموعه قابل شمارش مسیرهای کامل دایرکتوری‌های یافت‌شده که نام آن‌ها با **searchPattern** مطابقت دارد

## موارد مرتبط

* Enum [SearchOption](../../searchoption/)
* Typedef [StringEnumerablePtr](../stringenumerableptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)