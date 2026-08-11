---
title: GetDirectories()
second_title: Aspose.Slides برای مرجع API C++
description: آرایه‌ای را برمی‌گرداند که شامل shared pointers به اشیای DirectoryInfo است که تمام دایرکتوری‌های موجود در دایرکتوری نمایان‌شده توسط شیء فعلی را نشان می‌دهند.
type: docs
weight: 144
url: /fa/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() متد

آرایه‌ای را برمی‌گرداند که شامل shared pointers به اشیای [DirectoryInfo](../) است که تمام دایرکتوری‌های موجود در دایرکتوری نمایان‌شده توسط شیء جاری را نشان می‌دهند.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) متد

دایرکتوری‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند در دایرکتوری نمایان‌شده توسط شیء جاری جستجو می‌کند.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام دایرکتوری‌هایی که باید جستجو شوند |

### مقدار بازگشتی

آرایه‌ای از shared pointers به اشیای [DirectoryInfo](../) که دایرکتوری‌های یافت‌شده‌ای که نامشان با **searchPattern** مطابقت دارد را نشان می‌دهد.

## DirectoryInfo::GetDirectories(const String\&, SearchOption) متد

دایرکتوری‌هایی را که معیارهای جستجوی مشخص‌شده را برآورده می‌کنند یا در دایرکتوری نمایان‌شده توسط شیء جاری یا در کل درخت دایرکتوری ریشه‌دار در همان شیء جاری جستجو می‌کند.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```

### آرگومان‌ها

| پارامتر | نوع | توضیحات |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نام دایرکتوری‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو باید فقط در دایرکتوری نمایان‌شده توسط شیء جاری انجام شود یا در کل درخت دایرکتوری ریشه‌دار در همان شیء جاری |

### مقدار بازگشتی

آرایه‌ای از shared pointers به اشیای [DirectoryInfo](../) که دایرکتوری‌های یافت‌شده‌ای که نامشان با **searchPattern** مطابقت دارد را نشان می‌دهد.

## مراجع

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* کلاس [DirectoryInfo](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::IO](../../)
* کتابخانه [Aspose.Slides](../../../)