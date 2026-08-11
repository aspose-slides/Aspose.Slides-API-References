---
title: Directory
second_title: مرجع API برای Aspose.Slides برای C++
description: متدهایی برای دستکاری پوشه‌ها شامل می‌شود. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ وجه نمونه‌ای از آن ایجاد کنید.
type: docs
weight: 235
url: /fa/system.io/directory/
---
## Directory کلاس

متدهایی برای دستکاری پوشه‌ها شامل می‌شود. این یک نوع استاتیک بدون سرویس‌های نمونه است. شما هرگز نباید به هیچ راهی از آن نمونه‌ای ایجاد کنید.

```cpp
class Directory
```

## متدها

| متد | توضیح |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | تمام پوشه‌ها را در مسیر مشخص ایجاد می‌کند اگر وجود ندارند. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | فایل یا پوشهٔ مشخص‌شده را حذف می‌کند. استثنایی پرتاب نمی‌شود. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | پوشه‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | تعیین می‌کند آیا مسیر مشخص به یک پوشهٔ موجود اشاره دارد. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | زمان ایجاد موجودیت مشخص را به عنوان زمان محلی بازمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | زمان ایجاد موجودیت مشخص را به عنوان زمان UTC بازمی‌گرداند. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | نام کامل (شامل مسیر) پوشهٔ فعلی را بازمی‌گرداند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | پوشه‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | پوشه ریشه مسیر مشخص را بازمی‌گرداند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | فایل‌ها و پوشه‌هایی که معیارهای جستجوی مشخص را برآورده می‌شوند، یا در پوشهٔ مشخص یا در تمام درخت پوشه‌ها که ریشهٔ آن پوشهٔ مشخص است، جستجو می‌کند. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | آخرین زمان دسترسی به موجودیت مشخص را به عنوان زمان محلی بازمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | آخرین زمان دسترسی به موجودیت مشخص را به عنوان زمان UTC بازمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | آخرین زمان نوشتن موجودیت مشخص را به عنوان زمان محلی بازمی‌گرداند. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | آخرین زمان نوشتن موجودیت مشخص را به عنوان زمان UTC بازمی‌گرداند. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | پیاده‌سازی نشده. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | یک shared pointer به شیء [DirectoryInfo](../directoryinfo/) که نشانگر پوشه والد موجودیت مشخص است را بازمی‌گرداند. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | موجودیت مشخص را به مکان جدید منتقل می‌کند. اگر موجودیتی که منتقل می‌شود یک پوشه باشد، همراه با تمام محتوای آن منتقل می‌شود. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | زمان ایجاد موجودیت مشخص را به عنوان زمان محلی تنظیم می‌کند. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | زمان ایجاد موجودیت مشخص را به عنوان زمان UTC تنظیم می‌کند. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | پوشهٔ فعلی را تنظیم می‌کند. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان دسترسی به موجودیت مشخص را به عنوان زمان محلی تنظیم می‌کند. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان دسترسی به موجودیت مشخص را به عنوان زمان UTC تنظیم می‌کند. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیت مشخص را به عنوان زمان محلی تنظیم می‌کند. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | آخرین زمان نوشتن موجودیت مشخص را به عنوان زمان UTC تنظیم می‌کند. |

## تعاریف نوع

| تعریف‌نوع | توضیح |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | یک نام مستعار برای یک shared pointer به شیء IEnumerable که بر روی مجموعه‌ای از اشیای [String](../../system/string/) پیمایش می‌کند. |

## ملاحظات

```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // رشته‌هایی ایجاد می‌کند که مسیرهای پوشه‌ها را شامل می‌شوند.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // بررسی می‌کند که آیا پوشه‌ها وجود دارند یا خیر.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // اطلاعات پوشه موقت را چاپ می‌کند.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
این مثال کد خروجی زیر را تولید می‌کند:
پوشه 'C:\\' موجود است.
پوشه 'C:\\Some directory' موجود نیست.
پوشه 'C:\\Users\\lanor\\AppData\\Local\\Temp\\' موجود است.
زمان ایجاد: 27.08.2021 14:21:42
آخرین زمان دسترسی: 07.10.2021 12:16:41
آخرین زمان نوشتن: 07.10.2021 12:16:41
*/
```

## هم‌چنین ببینید

* فضای‌نام [System::IO](../)
* کتابخانه [Aspose.Slides](../../)