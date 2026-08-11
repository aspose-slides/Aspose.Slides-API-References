---
title: EnumerateDirectories()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الدلائل التي تلبي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.
type: docs
weight: 27
url: /ar/system.io/directory/enumeratedirectories/
---
## Directory::EnumerateDirectories(const String\&, const String\&, SearchOption) طريقة

يبحث عن الدلائل التي تلبي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي إلى الدليل المراد البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط الاسم الخاص بالدلائل التي يتم البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أم في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد |

### قيمة الإرجاع

مجموعة قابلة للتعدد من المسارات الكاملة للدلائل التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضاً

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [StringEnumerablePtr](../stringenumerableptr/)
* فئة [String](../../../system/string/)
* فئة [Directory](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)