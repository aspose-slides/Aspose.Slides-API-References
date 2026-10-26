---
title: Directory
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يحتوي على أساليب للتعامل مع الأدلة. هذا نوع ثابت بدون خدمات مثيلات. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.
type: docs
weight: 235
url: /ar/system.io/directory/
---
## فئة Directory


يحتوي على أساليب للتعامل مع الأدلة. هذا نوع ثابت بدون خدمات مثيلات. يجب ألا تقوم بإنشاء مثيلات له بأي وسيلة.

```cpp
class Directory
```

## الأساليب

| الطريقة | الوصف |
| --- | --- |
| static void [CreateDirectory_](./createdirectory_/)(const [String](../../system/string/)\&) | ينشئ جميع الأدلة في المسار المحدد إذا لم تكن موجودة. |
| static void [Delete](./delete/)(const [String](../../system/string/)\&, **bool**) | يزيل الملف أو الدليل المحدد. لا يرمي استثناءً. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateDirectories](./enumeratedirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الأدلة التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFiles](./enumeratefiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الملفات التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static [StringEnumerablePtr](./stringenumerableptr/) [EnumerateFileSystemEntries](./enumeratefilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الملفات والأدلة التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static **bool** [Exists](./exists/)(const [String](../../system/string/)\&) | يحدد ما إذا كان المسار المحدد يشير إلى دليل موجود. |
| static [DateTime](../../system/datetime/) [GetCreationTime](./getcreationtime/)(const [String](../../system/string/)\&) | يرجع وقت الإنشاء للكيان المحدد كوقت محلي. |
| static [DateTime](../../system/datetime/) [GetCreationTimeUtc](./getcreationtimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الإنشاء للكيان المحدد كوقت UTC. |
| static [String](../../system/string/) [GetCurrentDirectory](./getcurrentdirectory/)() | يرجع الاسم الكامل (بما في ذلك المسار) للدليل الحالي. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetDirectories](./getdirectories/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الأدلة التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static [String](../../system/string/) [GetDirectoryRoot](./getdirectoryroot/)(const [String](../../system/string/)\&) | يرجع دليل الجذر للمسار المحدد. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFiles](./getfiles/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الملفات التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetFileSystemEntries](./getfilesystementries/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, [SearchOption](../searchoption/)) | يبحث عن الملفات والأدلة التي تتطابق مع معايير البحث المحددة إما في الدليل المحدد أو في شجرة الدلائل الكاملة المتجذرة في الدليل المحدد. |
| static [DateTime](../../system/datetime/) [GetLastAccessTime](./getlastaccesstime/)(const [String](../../system/string/)\&) | يرجع وقت الوصول الأخير للكيان المحدد كوقت محلي. |
| static [DateTime](../../system/datetime/) [GetLastAccessTimeUtc](./getlastaccesstimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الوصول الأخير للكيان المحدد كوقت UTC. |
| static [DateTime](../../system/datetime/) [GetLastWriteTime](./getlastwritetime/)(const [String](../../system/string/)\&) | يرجع وقت الكتابة الأخير للكيان المحدد كوقت محلي. |
| static [DateTime](../../system/datetime/) [GetLastWriteTimeUtc](./getlastwritetimeutc/)(const [String](../../system/string/)\&) | يرجع وقت الكتابة الأخير للكيان المحدد كوقت UTC. |
| static [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [GetLogicalDrives](./getlogicaldrives/)() | غير مُنفَّذ. |
| static [DirectoryInfoPtr](../../system/directoryinfoptr/) [GetParent](./getparent/)(const [String](../../system/string/)\&) | يرجع مؤشرًا مشتركًا إلى كائن [DirectoryInfo](../directoryinfo/) يمثل الدليل الأب للكيان المحدد. |
| static void [Move](./move/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | ينقل الكيان المحدد إلى الموقع الجديد. إذا كان الكيان المنقول دليلًا، يتم نقله مع كل محتوياته. |
| static void [SetCreationTime](./setcreationtime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الإنشاء للكيان المحدد كوقت محلي. |
| static void [SetCreationTimeUtc](./setcreationtimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الإنشاء للكيان المحدد كوقت UTC. |
| static void [SetCurrentDirectory](./setcurrentdirectory/)(const [String](../../system/string/)\&) | يحدد الدليل الحالي. |
| static void [SetLastAccessTime](./setlastaccesstime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الوصول الأخير للكيان المحدد كوقت محلي. |
| static void [SetLastAccessTimeUtc](./setlastaccesstimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الوصول الأخير للكيان المحدد كوقت UTC. |
| static void [SetLastWriteTime](./setlastwritetime/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الكتابة الأخير للكيان المحدد كوقت محلي. |
| static void [SetLastWriteTimeUtc](./setlastwritetimeutc/)(const [String](../../system/string/)\&, [DateTime](../../system/datetime/)) | يحدد وقت الكتابة الأخير للكيان المحدد كوقت UTC. |

## الأنواع المعرفة

| النوع المعرف | الوصف |
| --- | --- |
| [StringEnumerablePtr](./stringenumerableptr/) | اسم مستعار لمؤشر مشترك إلى كائن IEnumerable الذي يعدّ مجموعة من كائنات [String](../../system/string/). |

## ملاحظات



```cpp
#include "system/io/directory.h"
#include "system/io/path.h"
#include "system/string.h"
#include <iostream>

void PrintMessage(const System::String &path)
{
  std::cout << "Directory '" << path << (System::IO::Directory::Exists(path) ? "' exists." : "' doesn't exist.") << std::endl;
}

int main()
{
  // إنشاء سلاسل تحتوي على مسارات إلى الأدلة.
  System::String discPath(u"C:\\");
  System::String directoryPath(u"C:\\Some directory");
  auto tempPath = System::IO::Path::GetTempPath();

  // تحقق مما إذا كانت الأدلة موجودة.
  PrintMessage(discPath);
  PrintMessage(directoryPath);
  PrintMessage(tempPath);

  // اطبع معلومات دليل المؤقت.
  std::cout <<
    "Creation Time: " << System::IO::Directory::GetCreationTime(tempPath) << std::endl <<
    "Last Access Time: " << System::IO::Directory::GetLastAccessTime(tempPath) << std::endl <<
    "Last Write Time: " << System::IO::Directory::GetLastWriteTime(tempPath) << std::endl;

  return 0;
}
/*
مثال الكود هذا ينتج المخرجات التالية:
الدليل 'C:\' موجود.
الدليل 'C:\Some directory' غير موجود.
الدليل 'C:\Users\lanor\AppData\Local\Temp\' موجود.
وقت الإنشاء: 27.08.2021 14:21:42
وقت آخر وصول: 07.10.2021 12:16:41
وقت آخر كتابة: 07.10.2021 12:16:41
*/
```

## انظر أيضًا

* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)