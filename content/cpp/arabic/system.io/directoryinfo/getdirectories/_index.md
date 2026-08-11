---
title: GetDirectories()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يعيد مصفوفة تحتوي على مؤشرات مشتركة إلى كائنات DirectoryInfo التي تمثل جميع الأدلة الموجودة في الدليل الممثل بواسطة الكائن الحالي.
type: docs
weight: 144
url: /ar/system.io/directoryinfo/getdirectories/
---
## DirectoryInfo::GetDirectories() طريقة


إرجاع مصفوفة تحتوي على مؤشرات مشتركة إلى كائنات [DirectoryInfo](../) تمثّل جميع الأدلة الموجودة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories()
```

## DirectoryInfo::GetDirectories(const String\&) طريقة


يبحث عن الأدلة التي تُحقق معايير البحث المحددة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الأدلة للبحث عنها |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى كائنات [DirectoryInfo](../) تمثّل الأدلة التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## DirectoryInfo::GetDirectories(const String\&, SearchOption) طريقة


يبحث عن الأدلة التي تُحقق معايير البحث المحددة إما في الدليل الذي يمثله الكائن الحالي أو في شجرة الأدلة الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي.

```cpp
ArrayPtr<DirectoryInfoPtr> System::IO::DirectoryInfo::GetDirectories(const String &searchPattern, SearchOption searchOption)
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الأدلة للبحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدّد ما إذا كان يجب إجراء البحث في الدليل الذي يمثله الكائن الحالي فقط أو في شجرة الأدلة الكاملة المتجذرة في الدليل الذي يمثله الكائن الحالي |

### قيمة الإرجاع

مصفوفة من المؤشرات المشتركة إلى كائنات [DirectoryInfo](../) تمثّل الأدلة التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضا

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)