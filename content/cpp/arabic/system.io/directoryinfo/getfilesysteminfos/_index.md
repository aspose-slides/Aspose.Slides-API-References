---
title: GetFileSystemInfos()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يُرجع مصفوفة تحتوي على مؤشرات مشتركة إلى كائنات FileSystemInfo تمثِّل جميع الملفات والمجلدات الموجودة في الدليل الذي يمثله الكائن الحالي.
type: docs
weight: 170
url: /ar/system.io/directoryinfo/getfilesysteminfos/
---
## DirectoryInfo::GetFileSystemInfos() طريقة

ترجع مصفوفة تحتوي على مؤشرات مشتركة إلى كائنات [FileSystemInfo](../../filesysteminfo/) تمثِّل جميع الملفات والمجلدات الموجودة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos()
```

## DirectoryInfo::GetFileSystemInfos(const String\&) طريقة

يبحث عن الملفات والمجلدات التي تستوفي معايير البحث المحددة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات والمجلدات للبحث عنها |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى كائنات [FileSystemInfo](../../filesysteminfo/) تمثِّل الملفات والمجلدات التي تم العثور عليها والتي تطابق أسماؤها **searchPattern**

## DirectoryInfo::GetFileSystemInfos(const String\&, SearchOption) طريقة


يبحث عن الملفات والمجلدات التي تستوفي معايير البحث المحددة إما في الدليل الذي يمثله الكائن الحالي أو في شجرة الدليل الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<FileSystemInfoPtr> System::IO::DirectoryInfo::GetFileSystemInfos(const String &searchPattern, SearchOption searchOption)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات والمجلدات للبحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل الذي يمثله الكائن الحالي فقط أو في شجرة الدليل الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى كائنات [FileSystemInfo](../../filesysteminfo/) تمثِّل الملفات والمجلدات التي تم العثور عليها والتي تطابق أسماؤها **searchPattern**

## انظر أيضًا

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [FileSystemInfoPtr](../../../system/filesysteminfoptr/)
* فئة [DirectoryInfo](../)
* فئة [String](../../../system/string/)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)