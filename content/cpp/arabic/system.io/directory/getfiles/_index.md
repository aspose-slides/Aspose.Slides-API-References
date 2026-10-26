---
title: GetFiles()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الملفات التي تلبي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدليل بالكامل المتجذرة في الدirectory المحدد.
type: docs
weight: 79
url: /ar/system.io/directory/getfiles/
---
## Directory::GetFiles(const String\&, const String\&, SearchOption) طريقة

يبحث عن الملفات التي تلبي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدليل بالكامل المتجذرة في الدليل المحدد.

```cpp
static ArrayPtr<String> System::IO::Directory::GetFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي إلى الدليل المراد البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات المراد البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أو في شجرة الدليل بالكامل المتجذرة في الدليل المحدد |

### قيمة الإرجاع

مصفوفة من المسارات الكاملة للملفات التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## انظر أيضًا

* Enum [SearchOption](../../searchoption/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [Directory](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)