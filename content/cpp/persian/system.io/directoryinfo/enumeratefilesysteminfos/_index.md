---
title: EnumerateFileSystemInfos()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه قابل شمارشی را برمی‌گرداند که شامل تمام فایل‌ها و پوشه‌های موجود در دایرکتوری نمایان‌ شده توسط شیء جاری است.
type: docs
weight: 131
url: /fa/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() متد


یک مجموعه قابل شمارش شامل تمام فایل‌ها و پوشه‌های موجود در دایرکتوری که توسط شیء جاری نمایان شده است را برمی‌گرداند.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```

## DirectoryInfo::EnumerateFileSystemInfos(const String\&) متد


فایل‌ها و پوشه‌هایی که معیار جستجوی مشخص‌شده را در دایرکتوری که توسط شیء جاری نمایان شده است، برآورده می‌کنند، جستجو می‌کند.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```


### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و پوشه‌هایی که باید جستجو شوند |

### مقدار بازگشت

مجموعه قابل شمارشی از اشاره‌گرهای اشتراکی به اشیاء [FileSystemInfo](../../filesysteminfo/) که نمایانگر فایل‌ها و پوشه‌های یافت‌شده‌ای هستند که نام آن‌ها با **searchPattern** مطابقت دارد

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) متد


فایل‌ها و پوشه‌هایی که معیار جستجوی مشخص‌شده را یا در دایرکتوری که توسط شیء جاری نمایان شده است یا در کل درخت دایرکتوری ریشه‌دار در آن دایرکتوری، جستجو می‌کند.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```


### آرگومان‌ها

| پارامتر | نوع | شرح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و پوشه‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو باید فقط در دایرکتوری که توسط شیء جاری نمایان شده است انجام شود یا در کل درخت دایرکتوری که از آن دایرکتوری ریشه دارد |

### مقدار بازگشت

مجموعه قابل شمارشی از اشاره‌گرهای اشتراکی به اشیاء [FileSystemInfo](../../filesysteminfo/) که نمایانگر فایل‌ها و پوشه‌های یافت‌شده‌ای هستند که نام آن‌ها با **searchPattern** مطابقت دارد

## مراجع

* شمارش [SearchOption](../../searchoption/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [DirectoryInfo](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)