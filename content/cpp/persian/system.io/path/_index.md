---
title: Path
second_title: Aspose.Slides برای C++ مرجع API
description: روش‌هایی برای دست‌کاری مسیرها فراهم می‌کند. این یک نوع استاتیک است که سرویس‌های نمونه‌ای ندارد. شما هرگز نباید به هیچ‌وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 339
url: /fa/system.io/path/
---
## کلاس Path

راهکارهایی برای دست کاری مسیرها فراهم می‌کند. این یک نوع استاتیک است که خدمات نمونه‌ای ندارد. شما نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.

```cpp
class Path
```

## متدها

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | پسوند را در مسیر فایل مشخص‌شده تغییر می‌دهد. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | تعیین می‌کند آیا مسیر مشخص‌شده معتبر است با بررسی اینکه آیا شامل کاراکترهای نامعتبر است یا خیر. اگر مسیر شامل کاراکترهای نامعتبر باشد، استثنایی پرتاب می‌شود. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | بخش‌های مسیر مشخص‌شده را در یک مسیر واحد ترکیب می‌کند و در صورت نیاز کاراکترهای جداکنندهٔ پوشه را بین بخش‌ها درج می‌کند. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | دو بخش مسیر مشخص‌شده را در یک مسیر واحد ترکیب می‌کند و در صورت نیاز کاراکتر جداکنندهٔ پوشه را بین بخش‌ها درج می‌کند. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | سه بخش مسیر مشخص‌شده را در یک مسیر واحد ترکیب می‌کند و در صورت نیاز کاراکترهای جداکنندهٔ پوشه را بین بخش‌ها درج می‌کند. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | چهار بخش مسیر مشخص‌شده را در یک مسیر واحد ترکیب می‌کند و در صورت نیاز کاراکترهای جداکنندهٔ پوشه را بین بخش‌ها درج می‌کند. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | نام دایرکتوری را که توسط مسیر مشخص‌شده ارجاع داده شده است برمی‌گرداند. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | پسوند فایل را که توسط مسیر مشخص‌شده ارجاع داده شده است برمی‌گرداند. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | نام فایل را که توسط مسیر مشخص‌شده ارجاع داده شده است برمی‌گرداند. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | نام فایل بدون پسوند را که توسط مسیر مشخص‌شده ارجاع داده شده است برمی‌گرداند. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | مسیر مشخص‌شده را به مسیر مطلق تبدیل می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | آرایه‌ای شامل کاراکترهایی که در نام‌ فایل‌ها مجاز نیستند برمی‌گرداند. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | آرایه‌ای شامل کاراکترهایی که در نام مسیرها مجاز نیستند برمی‌گرداند. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | دایرکتوری ریشهٔ مسیر مشخص‌شده را برمی‌گرداند. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | نام فایل تصادفی تولید شده را برمی‌گرداند. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | فایلی جدید با نام یکتا ایجاد می‌کند و مسیر کامل آن را برمی‌گرداند. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | فایلی جدید با نام یکتا ایجاد می‌کند و مسیر کامل آن را برمی‌گرداند. مترادف روش [GetTempFileName_()](./gettempfilename_/) است. |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | مسیر دایرکتوری موقت کاربر جاری را برمی‌گرداند. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | تعیین می‌کند آیا مسیر مشخص‌شده به فایلی با پسوند ارجاع می‌دهد. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | تعیین می‌کند آیا مسیر مشخص‌شده شامل ریشه است. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | مسیر مشخص‌شده را نرمال‌سازی می‌کند. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | نمونه‌ای از کلاس boost::filesystem::path که مسیر مشخص‌شده را نشان می‌دهد برمی‌گرداند. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | نمایش رشته‌ای از شیء مسیر Boost مشخص‌شده را برمی‌گرداند. |

## فیلدها

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | کاراکتر جایگزین برای جدا کردن سطوح دایرکتوری در یک مسیر. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | کاراکتر برای جدا کردن سطوح دایرکتوری در یک مسیر. |
| static [PathSeparator](./pathseparator/) | کاراکتر جداکننده‌ای که برای جدا کردن رشته‌های مسیر در متغیرهای محیطی استفاده می‌شود. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | کاراکتر جداکنندهٔ حجم. |

## یادداشت‌ها

```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // یک نام فایل تصادفی تولید می‌کند.
  auto filename = Path::GetRandomFileName();

  // اطلاعات مربوط به نام فایل را چاپ می‌کند.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
این نمونه کد خروجی زیر را تولید می‌کند:
Filename: qhuzkyqv.y6p
Filename w/o an extension: qhuzkyqv
Extension: .y6p
*/
```

## موارد مرتبط

* فضای نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)