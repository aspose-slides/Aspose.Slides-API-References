---
title: EnumerateFiles()
second_title: Aspose.Slides برای C++ مرجع API
description: یک مجموعه قابل‌تجمیع شامل همه فایل‌های موجود در دایرکتوری که توسط شیء جاری نمایان شده است را برمی‌گرداند.
type: docs
weight: 118
url: /fa/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() متد

یک مجموعه قابل‌تجمیع شامل همه فایل‌های موجود در دایرکتوری که توسط شیء جاری نمایان شده است را برمی‌گرداند.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```

## DirectoryInfo::EnumerateFiles(const String\&) متد

فایل‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند در دایرکتوری که توسط شیء جاری نمایان شده است جستجو می‌کند.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگو نامی فایل‌هایی که باید جستجو شوند |

### مقدار بازگشتی

مجموعه قابل‌تجمیع از اشاره‌گرهای مشترک به اشیاء [FileInfo](../../fileinfo/) که فایل‌های یافت‌شده را که نام آن‌ها با **searchPattern** مطابقت دارد، نمایندگی می‌کند.

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) متد

فایل‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند، چه در دایرکتوری که توسط شیء جاری نمایان شده است و چه در کل درخت دایرکتوری ریشه‌دار در آن دایرکتوری جستجو می‌کند.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگو نامی فایل‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو فقط باید در دایرکتوری که توسط شیء جاری نمایان شده است انجام شود یا در کل درخت دایرکتوری ریشه‌دار در آن دایرکتوری |

### مقدار بازگشتی

مجموعه قابل‌تجمیع از اشاره‌گرهای مشترک به اشیاء [FileInfo](../../fileinfo/) که فایل‌های یافت‌شده را که نام آن‌ها با **searchPattern** مطابقت دارد، نمایندگی می‌کند.

## همچنین ببینید

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)