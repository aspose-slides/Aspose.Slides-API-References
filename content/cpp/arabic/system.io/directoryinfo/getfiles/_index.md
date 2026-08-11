---
title: GetFiles()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يَرجِع مصفوفة تحتوي على مؤشرات مشتركة إلى كائنات FileInfo تمثّل جميع الأدلة الموجودة في الدليل الذي يمثّله الكائن الحالي.
type: docs
weight: 157
url: /ar/system.io/directoryinfo/getfiles/
---
## DirectoryInfo::GetFiles() طريقة

تُرجِع مصفوفة تحتوي على مؤشرات مشتركة إلى [FileInfo](../../fileinfo/) تمثّل جميع الأدلة الموجودة في الدليل الذي يمثّله الكائن الحالي.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles()
```

## DirectoryInfo::GetFiles(const String\&) طريقة

يبحث عن الملفات التي تفي بمعايير البحث المحدّدة في الدليل الذي يمثّله الكائن الحالي.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern)
```

### معاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات المراد البحث عنها |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى [FileInfo](../../fileinfo/) تمثّل الملفات التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## DirectoryInfo::GetFiles(const String\&, SearchOption) طريقة

يبحث عن الملفات التي تفي بمعايير البحث المحدّدة إما في الدليل الذي يمثّله الكائن الحالي أو في شجرة الأدلة الكاملة المتجذرة في الدليل الذي يمثّله الكائن الحالي.

```cpp
ArrayPtr<FileInfoPtr> System::IO::DirectoryInfo::GetFiles(const String &searchPattern, SearchOption searchOption)
```

### معاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات المراد البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدّد ما إذا كان يجب إجراء البحث في الدليل الذي يمثّله الكائن الحالي فقط أو في شجرة الأدلة الكاملة المتجذرة في الدليل الذي يمثّله الكائن الحالي |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى [FileInfo](../../fileinfo/) تمثّل الملفات التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضًا

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [FileInfoPtr](../../../system/fileinfoptr/)
* فئة [DirectoryInfo](../)
* فئة [String](../../../system/string/)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)