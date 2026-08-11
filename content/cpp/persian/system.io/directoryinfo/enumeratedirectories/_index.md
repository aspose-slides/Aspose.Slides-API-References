---
title: EnumerateDirectories()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه‌ای قابل شمارش را برمی‌گرداند که شامل تمام دایرکتوری‌های موجود در دایرکتوری نمایانگر شیء جاری است.
type: docs
weight: 105
url: /fa/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() متد

مجموعه‌ای قابل شمارش را برمی‌گرداند که شامل تمام دایرکتوری‌های موجود در دایرکتوری نمایانگر شیء جاری است.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) متد

دایرکتوری‌هایی را جستجو می‌کند که مطابق معیارهای جستجوی مشخص‌شده در دایرکتوری نمایانگر شیء جاری باشند.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نامی دایرکتوری‌ها برای جستجو |

### مقدار بازگشت

مجموعه قابل شمارش از نشانگرهای اشتراکی به اشیای [DirectoryInfo](../) که نمایانگر دایرکتوری‌های یافت شده‌ای هستند که نام‌هایشان با **searchPattern** مطابقت دارد

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) متد

دایرکتوری‌هایی را جستجو می‌کند که مطابق معیارهای جستجوی مشخص‌شده یا در دایرکتوری نمایانگر شیء جاری یا در کل درخت دایرکتوری که در آن دایرکتوری ریشه دارد، باشند.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نامی دایرکتوری‌ها برای جستجو |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو فقط در دایرکتوری نمایانگر شیء جاری انجام شود یا در کل درخت دایرکتوری که ریشه آن همان دایرکتوری است |

### مقدار بازگشت

مجموعه قابل شمارش از نشانگرهای اشتراکی به اشیای [DirectoryInfo](../) که نمایانگر دایرکتوری‌های یافت شده‌ای هستند که نام‌هایشان با **searchPattern** مطابقت دارد

## موارد مرتبط

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* کلاس [IEnumerable](../../../system.collections.generic/ienumerable/)
* کلاس [DirectoryInfo](../)
* کلاس [String](../../../system/string/)
* فضای‌نام [System::IO](../../)
* Library [Aspose.Slides](../../../)