---
title: EnumerateFileSystemInfos()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يرجع مجموعة قابلة للتعداد تحتوي على جميع الملفات والمسارات الموجودة في الدليل الممثل بالكائن الحالي.
type: docs
weight: 131
url: /ar/system.io/directoryinfo/enumeratefilesysteminfos/
---
## DirectoryInfo::EnumerateFileSystemInfos() طريقة

يرجع مجموعة قابلة للتعداد تحتوي على جميع الملفات والمسارات الموجودة في الدليل الممثل بالكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos()
```
## DirectoryInfo::EnumerateFileSystemInfos(const String\&) طريقة

يبحث عن الملفات والمسارات التي تلبي معايير البحث المحددة في الدليل الممثل بالكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات والمسارات التي يتم البحث عنها |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [FileSystemInfo](../../filesysteminfo/) التي تمثل الملفات والمسارات التي تتطابق أسماؤها مع **searchPattern**

## DirectoryInfo::EnumerateFileSystemInfos(const String\&, SearchOption) طريقة

يبحث عن الملفات والمسارات التي تلبي معايير البحث المحددة إما في الدليل الممثل بالكائن الحالي أو في شجرة الدليل الكاملة المتجذرة في الدليل الممثل بالكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileSystemInfoPtr>> System::IO::DirectoryInfo::EnumerateFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات والمسارات التي يتم البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل الممثل بالكائن الحالي فقط أو في شجرة الدليل الكاملة المتجذرة في الدليل الممثل بالكائن الحالي |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [FileSystemInfo](../../filesysteminfo/) التي تمثل الملفات والمسارات التي تتطابق أسماؤها مع **searchPattern**

## انظر أيضًا

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)