---
title: EnumerateFiles()
second_title: مرجع Aspose.Slides للغة C++
description: إرجاع مجموعة قابلة للتعداد تحتوي على جميع الملفات الموجودة في الدليل الذي يمثله الكائن الحالي.
type: docs
weight: 118
url: /ar/system.io/directoryinfo/enumeratefiles/
---
## DirectoryInfo::EnumerateFiles() طريقة

إرجاع مجموعة قابلة للتعداد تحتوي على جميع الملفات الموجودة في الدليل الذي يمثله الكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles()
```
## DirectoryInfo::EnumerateFiles(const String\&) طريقة

البحث عن الملفات التي تلبي معايير البحث المحددة في الدليل الذي يمثله الكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات للبحث عنها |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [FileInfo](../../fileinfo/) التي تمثل الملفات المكتشفة والتي تتطابق أسماؤها مع **searchPattern**.

## DirectoryInfo::EnumerateFiles(const String\&, SearchOption) طريقة

البحث عن الملفات التي تلبي معايير البحث المحددة إما في الدليل الذي يمثله الكائن الحالي أو في شجرة الدليل الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي.

```cpp
SharedPtr<IEnumerable<FileInfoPtr>> System::IO::DirectoryInfo::EnumerateFiles(const String &searchPattern, SearchOption searchOption)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات للبحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل الذي يمثله الكائن الحالي فقط أو في شجرة الدليل الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [FileInfo](../../fileinfo/) التي تمثل الملفات المكتشفة والتي تتطابق أسماؤها مع **searchPattern**.

## انظر أيضاً

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [FileInfoPtr](../../../system/fileinfoptr/)
* فئة [IEnumerable](../../../system.collections.generic/ienumerable/)
* فئة [DirectoryInfo](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)