---
title: GetFileSystemEntries()
second_title: Aspose.Slides برای C++ مرجع API
description: فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، یا در پوشهٔ مشخص‌شده یا در کل درخت پوشه‌ها که از پوشهٔ مشخص‌شده ریشه دارد، جستجو می‌کند.
type: docs
weight: 92
url: /fa/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String&, const String&, SearchOption) متد

فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص شده را برآورده می‌کنند، یا در پوشهٔ مشخص‌شده یا در تمام درخت پوشه‌ها که از پوشهٔ مشخص‌شده ریشه‌دار است، جستجو می‌کند.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی به پوشه‌ای که جستجو در آن انجام می‌شود |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و پوشه‌هایی که جستجو می‌شود |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو باید فقط در پوشهٔ مشخص‌شده انجام شود یا در تمام درخت پوشه‌ها که از پوشهٔ مشخص‌شده ریشه‌دار است |

### مقدار بازگشتی

آرایه‌ای از مسیرهای کامل فایل‌ها و پوشه‌های یافت‌شده که نام آن‌ها با **searchPattern** مطابقت دارد

## موارد مرتبط

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)