---
title: EnumerateFiles()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يبحث عن الملفات التي تلبي معايير البحث المحددة إما في الدليل المحدد أو في شجرة الأدلة الكاملة المتجذرة في الدليل المحدد.
type: docs
weight: 40
url: /ar/system.io/directory/enumeratefiles/
---
## Directory::EnumerateFiles(const String\&, const String\&, SearchOption) طريقة


Searches for the files that satisfy the specified search criteria either in the specified directory or in the whole directory tree rooted in the specified directory.

```cpp
static StringEnumerablePtr System::IO::Directory::EnumerateFiles(const String &path, const String &searchPattern=u"*", SearchOption searchOption=SearchOption::TopDirectoryOnly)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار الكامل أو النسبي إلى الدليل الذي يتم البحث فيه |
| searchPattern | const [String](../../../system/string/)\& | نمط اسم الملفات المراد البحث عنها |
| searchOption | [SearchOption](../../searchoption/) | يحدد ما إذا كان يجب إجراء البحث في الدليل المحدد فقط أو في شجرة الأدلة الكاملة التي جذورها الدليل المحدد |

### Return Value

مجموعة قابلة للتعداد من المسارات الكاملة للملفات التي تم العثور عليها والتي تتطابق أسماؤها مع **searchPattern**

## See Also

* تعداد [SearchOption](../../searchoption/)
* تعريف نوع [StringEnumerablePtr](../stringenumerableptr/)
* فئة [String](../../../system/string/)
* فئة [Directory](../)
* نطاق الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)