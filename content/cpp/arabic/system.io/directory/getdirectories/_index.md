---
title: GetDirectories()
second_title: Aspose.Slides لواجهة برمجة التطبيقات C++
description: يبحث عن الأدلة التي تفي بمعايير البحث المحددة إما في الدليل المحدد أو في شجرة الأدلة الكاملة التي جذورها في الدليل المحدد.
type: docs
weight: 66
url: /ar/system.io/directory/getdirectories/
---
## Directory::GetDirectories(const String\&, const String\&, SearchOption) طريقة

يبحث عن الأدلة التي تفي بمعايير البحث المحددة إما في الدليل المحدد أو في شجرة الأدلة الكاملة التي جذورها في الدليل المحدد.

```cpp
static ArrayPtr<String> System::IO::Directory::GetDirectories(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي للدليل الذي يُجري البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الأدلة التي يبحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أو في شجرة الأدلة الكاملة التي جذورها في الدليل المحدد |

### قيمة الإرجاع

مصفوفة من المسارات الكاملة للأدلة التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## أنظر أيضًا

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)