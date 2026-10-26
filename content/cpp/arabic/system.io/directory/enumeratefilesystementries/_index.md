---
title: EnumerateFileSystemEntries()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يبحث عن الملفات والدلائل التي تستوفي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.
type: docs
weight: 53
url: /ar/system.io/directory/enumeratefilesystementries/
---
## Directory::EnumerateFileSystemEntries(const String\&, const String\&, SearchOption) طريقة

يبحث عن الملفات والدلائل التي تستوفي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي إلى الدليل الذي يتم البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط الاسم للملفات والدلائل التي يتم البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد |

### قيمة الإرجاع

المجموعة القابلة للتعداد من المسارات الكاملة للملفات والدلائل التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضاً

* تعداد [SearchOption](../../searchoption/)
* نوع معرف [StringEnumerablePtr](../stringenumerableptr/)
* فئة [String](../../../system/string/)
* فئة [Directory](../)
* نطاق [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)