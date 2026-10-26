---
title: GetFileSystemEntries()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الملفات والدلائل التي تستوفي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.
type: docs
weight: 92
url: /ar/system.io/directory/getfilesystementries/
---
## Directory::GetFileSystemEntries(const String\&, const String\&, SearchOption) طريقة

يبحث عن الملفات والدلائل التي تستوفي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFileSystemEntries(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي إلى الدليل الذي سيتم البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات والدلائل للبحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد |

### قيمة الإرجاع

مصفوفة من المسارات الكاملة للملفات والدلائل التي تم العثور عليها والتي تطابق أسماؤها **searchPattern**

## انظر أيضاً

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [String](../../../system/string/)
* فئة [Directory](../)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)