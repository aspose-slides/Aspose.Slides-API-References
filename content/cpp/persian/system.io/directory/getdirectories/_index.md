---
title: GetDirectories()
second_title: مرجع API Aspose.Slides برای C++
description: دایرکتوری‌هایی را جستجو می‌کند که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در دایرکتوری مشخص‌شده و چه در کل درخت دایرکتوری که از دایرکتوری مشخص‌شده ریشه دارد.
type: docs
weight: 66
url: /fa/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) متد

دایرکتوری‌ها را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در دایرکتوری مشخص‌شده و چه در کل درخت دایرکتوری که از دایرکتوری مشخص‌شده ریشه دارد، جستجو می‌کند.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی به دایرکتوری که باید در آن جستجو شود |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام دایرکتوری‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو باید فقط در دایرکتوری مشخص‌شده انجام شود یا در کل درخت دایرکتوری که از دایرکتوری مشخص‌شده ریشه دارد |

### مقدار بازگشت

آرایه‌ای از مسیرهای کامل دایرکتوری‌های یافت‌شده که نام آن‌ها با **searchPattern** مطابقت دارد

## مراجعه

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)