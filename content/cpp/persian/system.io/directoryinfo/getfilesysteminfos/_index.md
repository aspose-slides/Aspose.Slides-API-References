---
title: GetFileSystemInfos()
second_title: مرجع API Aspose.Slides برای C++
description: آرایه‌ای شامل اشاره‌گرهای مشترک به اشیاء FileSystemInfo که نمایانگر تمام فایل‌ها و پوشه‌های موجود در دایرکتوری نمایانده‌شده توسط شیء فعلی هستند را برمی‌گرداند.
type: docs
weight: 170
url: /fa/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() متد

آرایه‌ای شامل اشاره‌گرهای مشترک به اشیاء [FileSystemInfo](../../filesysteminfo/) که نمایانگر تمام فایل‌ها و پوشه‌های موجود در دایرکتوری نمایانده‌شده توسط شیء فعلی هستند، بر می‌گرداند.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) متد

فایل‌ها و پوشه‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند در دایرکتوری نمایانده‌شده توسط شیء فعلی جستجو می‌کند.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و پوشه‌هایی که باید جستجو شوند |

### مقدار بازگشتی

آرایه‌ای از اشاره‌گرهای مشترک به اشیاء [FileSystemInfo](../../filesysteminfo/) که نمایانگر فایل‌ها و پوشه‌های یافت‌شده‌ای هستند که نام آن‌ها با **searchPattern** مطابقت دارد.

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) متد

فایل‌ها و پوشه‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، در دایرکتوری نمایانده‌شده توسط شیء فعلی یا در تمام درخت دایرکتوری ریشه‌دار در آن دایرکتوری جستجو می‌کند.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام فایل‌ها و پوشه‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که جستجو فقط در دایرکتوری نمایانده‌شده توسط شیء فعلی انجام شود یا در تمام درخت دایرکتوری ریشه‌دار در آن دایرکتوری |

### مقدار بازگشتی

آرایه‌ای از اشاره‌گرهای مشترک به اشیاء [FileSystemInfo](../../filesysteminfo/) که نمایانگر فایل‌ها و پوشه‌های یافت‌شده‌ای هستند که نام آن‌ها با **searchPattern** مطابقت دارد.

## موارد مرتبط

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)