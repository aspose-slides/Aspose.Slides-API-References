---
title: Replace()
second_title: مرجع API Aspose.Slides برای C++
description: محتوای یک فایل مقصد مشخص را با فایلی که توسط شیء FileInfo جاری نمایندگی می‌شود جایگزین می‌کند و یک نسخه پشتیبان از فایل جایگزین‌شده ایجاد می‌کند.
type: docs
weight: 131
url: /fa/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) متد

محتویات یک فایل مقصد مشخص را با فایلی که توسط شیء [FileInfo](../) جاری نمایندگی می‌شود جایگزین می‌کند و یک نسخه پشتیبان از فایل جایگزین‌شده ایجاد می‌کند.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | نام فایل برای جایگزینی |
| destinationBackupFileName | const [String](../../../system/string/)\& | نام فایل پشتیبان |

### مقدار بازگشت

یک شیء FileInfor که نمایانگر فایلی است که توسط **destinationFileName** اشاره شده است

## FileInfo::Replace(const String\&, const String\&, bool) متد

محتویات یک فایل مقصد مشخص را با فایلی که توسط شیء [FileInfo](../) جاری نمایندگی می‌شود جایگزین می‌کند و یک نسخه پشتیبان از فایل جایگزین‌شده ایجاد می‌کند.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | نام فایل برای جایگزینی |
| destinationBackupFileName | const [String](../../../system/string/)\& | نام فایل پشتیبان |
| ignoreMetadataErrors | **bool** | مشخص می‌کند که خطاهای ادغام از فایل جایگزین‌شده به فایل جایگزین نادیده گرفته شوند (true) یا نه (false) |

### مقدار بازگشت

یک شیء FileInfor که نمایانگر فایلی است که توسط **destinationFileName** اشاره شده است

## موارد مرتبط

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)