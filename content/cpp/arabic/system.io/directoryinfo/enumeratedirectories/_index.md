---
title: EnumerateDirectories()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: تُرجِع مجموعة قابلة للتعداد تحتوي على جميع الأدلة الموجودة في الدليل المُمثل بواسطة الكائن الحالي.
type: docs
weight: 105
url: /ar/system.io/directoryinfo/enumeratedirectories/
---
## DirectoryInfo::EnumerateDirectories() طريقة

تُرجِع مجموعة قابلة للتعداد تحتوي على جميع الأدلة الموجودة في الدليل المُمثل بواسطة الكائن الحالي.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories()
```

## DirectoryInfo::EnumerateDirectories(const String\&) طريقة

تبحث عن الأدلة التي تتوافق مع المعايير المحددة للبحث في الدليل المُمثل بواسطة الكائن الحالي.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط الاسم للأدلة المراد البحث عنها |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [DirectoryInfo](../) التي تمثل الأدلة التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## DirectoryInfo::EnumerateDirectories(const String\&, SearchOption) طريقة

تبحث عن الأدلة التي تتوافق مع المعايير المحددة للبحث إما في الدليل المُمثل بواسطة الكائن الحالي أو في شجرة الدليل بأكملها المتجذرة في الدليل المُمثل بواسطة الكائن الحالي.

```cpp
SharedPtr<IEnumerable<DirectoryInfoPtr>> System::IO::DirectoryInfo::EnumerateDirectories(const String &searchPattern, SearchOption searchOption)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| searchPattern | const [String](../../../system/string/)\& | نمط الاسم للأدلة المراد البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المُمثل بواسطة الكائن الحالي فقط أو في شجرة الدليل بأكملها المتجذرة في الدليل المُمثل بواسطة الكائن الحالي |

### قيمة الإرجاع

مجموعة قابلة للتعداد من المؤشرات المشتركة إلى كائنات [DirectoryInfo](../) التي تمثل الأدلة التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضًا

* Enum [SearchOption](../../searchoption/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [DirectoryInfoPtr](../../../system/directoryinfoptr/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [DirectoryInfo](../)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)