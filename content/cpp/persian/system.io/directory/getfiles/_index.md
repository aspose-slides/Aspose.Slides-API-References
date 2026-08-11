---
title: GetFiles()
second_title: Aspose.Slides برای C++ مرجع API
description: فایل‌هایی را جستجو می‌کند که معیارهای جستجوی مشخص‌شده را برآورده کنند، چه در پوشهٔ مشخص‌شده و چه در کل درخت پوشهٔ ریشه‌دار آن پوشه.
type: docs
weight: 79
url: /fa/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) متد

جستجو برای فایل‌هایی که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در پوشهٔ مشخص‌شده و چه در کل درخت پوشهٔ ریشه‌دار در پوشهٔ مشخص‌شده.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسیر کامل یا نسبی پوشه‌ای که قرار است جستجو در آن انجام شود |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | تعیین می‌کند که جستجو فقط در پوشهٔ مشخص‌شده انجام شود یا در کل درخت پوشهٔ ریشه‌دار در پوشهٔ مشخص‌شده |

### Return Value

یک آرایه از مسیرهای کامل فایل‌های پیدا شده که نام آن‌ها با **searchPattern** مطابقت دارد

## See Also

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [String](../../../system/string/)
* کلاس [Directory](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)