---
title: CopyTo()
second_title: مرجع API Aspose.Slides برای C++
description: فایلی که توسط شیء فعلی نمایندگی می‌شود را به مکان تعیین‌شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، عملیات کپی ناموفق می‌شود.
type: docs
weight: 105
url: /fa/system.io/fileinfo/copyto/
---
## FileInfo::CopyTo(const String\&) متد

فایلی که توسط شیء فعلی نمایندگی می‌شود را به مکان تعیین‌شده کپی می‌کند. اگر فایل مقصد از قبل وجود داشته باشد، عملیات کپی ناموفق می‌شود.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | نام فایل مقصد |

### Return Value

یک شیء [FileInfo](../) که نمایانگر نسخه کپی است

## FileInfo::CopyTo(const String\&, bool) متد

فایلی که توسط شیء فعلی نمایندگی می‌شود را به مکان تعیین‌شده کپی می‌کند. یک پارامتر مشخص می‌کند که آیا فایل مقصد موجود باید بازنویسی شود یا خیر.

```cpp
FileInfoPtr System::IO::FileInfo::CopyTo(const String &destFileName, bool overwrite)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| destFileName | const [String](../../../system/string/)\& | نام فایل مقصد |
| overwrite | **bool** | اگر فایل مقصد موجود باید بازنویسی شود مقدار true، اگر در صورت وجود فایل مقصد کپی باید شکست بخورد مقدار false |

### Return Value

یک شیء [FileInfo](../) که نمایانگر نسخه کپی است

## موارد مرتبط

* تعریف نوع [FileInfoPtr](../../../system/fileinfoptr/)
* کلاس [String](../../../system/string/)
* کلاس [FileInfo](../)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)