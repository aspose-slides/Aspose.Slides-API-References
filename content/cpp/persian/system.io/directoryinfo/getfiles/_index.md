---
title: GetFiles()
second_title: مرجع API Aspose.Slides برای C++
description: یک آرایه شامل اشاره‌گرهای مشترک به اشیاء FileInfo که تمام پوشه‌های موجود در پوشه‌ای که توسط شیء جاری نمایان شده است را توصیف می‌کند، برمی‌گرداند.
type: docs
weight: 157
url: /fa/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() متد

یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [FileInfo](../../fileinfo/) که تمام پوشه‌های موجود در پوشه‌ای که توسط شیء جاری نمایان شده است را توصیف می‌کند، برمی‌گرداند.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) متد

فایل‌هایی که معیارهای جستجوی مشخص‌شده را در پوشه‌ای که توسط شیء جاری نمایان شده است، برآورده می‌کنند، جستجو می‌کند.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نامی فایل‌هایی که باید جستجو شوند |

### مقدار بازگشت

یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [FileInfo](../../fileinfo/) که فایل‌های پیدا شده‌ای را که نامشان با **searchPattern** مطابقت دارد، نشان می‌دهد.

## DirectoryInfo::GetFiles(const String\&, SearchOption) متد

فایل‌هایی که معیارهای جستجوی مشخص‌شده را یا در پوشه‌ای که توسط شیء جاری نمایان شده است یا در تمام درخت پوشه‌ای که ریشه آن همان پوشه است، جستجو می‌کند.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | الگوی نامی فایل‌هایی که باید جستجو شوند |
| searchOption | [SearchOption](../../searchoption/) | مشخص می‌کند که آیا جستجو فقط در پوشه‌ای که توسط شیء جاری نمایان شده است یا در تمام درخت پوشه‌ای که ریشه آن همان پوشه است انجام شود |

### مقدار بازگشت

یک آرایه شامل اشاره‌گرهای مشترک به اشیاء [FileInfo](../../fileinfo/) که فایل‌های پیدا شده‌ای را که نامشان با **searchPattern** مطابقت دارد، نشان می‌دهد.

## نگاه کنید به

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* کلاس [DirectoryInfo](../)
* کلاس [String](../../../system/string/)
* نام‌فضا [System::IO](../../)
* Library [Aspose.Slides](../../../)