---
title: Path
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يوفر طرقًا لمعالجة المسارات. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ مثيلات منه بأي طريقة.
type: docs
weight: 339
url: /ar/system.io/path/
---
## فئة Path

يوفر طرقًا لمعالجة المسارات. هذا نوع ثابت لا يحتوي على خدمات مثيل. يجب ألا تنشئ مثيلات منه بأي طريقة.

```cpp
class Path
```

## الطرق

| Method | Description |
| --- | --- |
| static [String](../../system/string/) [ChangeExtension](./changeextension/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يغيّر الامتداد في مسار الملف المحدد. |
| static void [CheckPath](./checkpath/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, **bool**) | يحدد ما إذا كان المسار المحدد صحيحًا عن طريق فحص ما إذا كان يحتوي على أحرف غير صالحة. يتم إطلاق استثناء إذا كان المسار يحتوي على أحرف غير صالحة. |
| static [String](../../system/string/) [Combine](./combine/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | يجمع مقاطع المسار المحددة في مسار واحد مع إدراج أحرف فاصل المجلدات بين المقاطع إذا لزم الأمر. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يجمع مقطعين محددين من المسار في مسار واحد مع إدراج حرف فاصل المجلدات بين المقاطع إذا لزم الأمر. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يجمع ثلاثة مقاطع مسار محددة في مسار واحد مع إدراج أحرف فاصل المجلدات بين المقاطع إذا لزم الأمر. |
| static [String](../../system/string/) [Combine](./combine/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&, const [String](../../system/string/)\&) | يجمع أربعة مقاطع مسار محددة في مسار واحد مع إدراج أحرف فاصل المجلدات بين المقاطع إذا لزم الأمر. |
| static [String](../../system/string/) [GetDirectoryName](./getdirectoryname/)(const [String](../../system/string/)\&) | يرجع اسم المجلد المشار إليه بالمسار المحدد. |
| static [String](../../system/string/) [GetExtension](./getextension/)(const [String](../../system/string/)\&) | يرجع امتداد الملف المشار إليه بالمسار المحدد. |
| static [String](../../system/string/) [GetFileName](./getfilename/)(const [String](../../system/string/)\&) | يرجع اسم الملف المشار إليه بالمسار المحدد. |
| static [String](../../system/string/) [GetFileNameWithoutExtension](./getfilenamewithoutextension/)(const [String](../../system/string/)\&) | يرجع اسم الملف بدون امتداد للملف المشار إليه بالمسار المحدد. |
| static [String](../../system/string/) [GetFullPath](./getfullpath/)(const [String](../../system/string/)\&) | يحول المسار المحدد إلى مسار مطلق. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidFileNameChars](./getinvalidfilenamechars/)() | يرجع مصفوفة تحتوي على الأحرف غير المسموح بها في أسماء الملفات. |
| static [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetInvalidPathChars](./getinvalidpathchars/)() | يرجع مصفوفة تحتوي على الأحرف غير المسموح بها في أسماء المسارات. |
| static [String](../../system/string/) [GetPathRoot](./getpathroot/)(const [String](../../system/string/)\&) | يرجع دليل الجذر للمسار المحدد. |
| static [String](../../system/string/) [GetRandomFileName](./getrandomfilename/)() | يرجع اسم ملف عشوائي تم إنشاؤه. |
| static [String](../../system/string/) [GetTempFileName_](./gettempfilename_/)() | ينشئ ملفًا جديدًا باسم فريد ويُرجع مسارًا كاملاً له. |
| static [String](../../system/string/) [GetTempFileNameSafe](./gettempfilenamesafe/)() | ينشئ ملفًا جديدًا باسم فريد ويُرجع مسارًا كاملاً له. هو مرادف للطريقة [GetTempFileName_()](./gettempfilename_/). |
| static [String](../../system/string/) [GetTempPath](./gettemppath/)() | يرجع مسار مجلد المؤقت للمستخدم الحالي. |
| static **bool** [HasExtension](./hasextension/)(const [String](../../system/string/)\&) | يحدد ما إذا كان المسار المحدد يشير إلى ملف بامتداد. |
| static **bool** [IsPathRooted](./ispathrooted/)(const [String](../../system/string/)\&) | يحدد ما إذا كان المسار المحدد يحتوي على جذر. |
| static [String](../../system/string/) [NormalizePath](./normalizepath/)(const [String](../../system/string/)\&) | يقوم بتطبيع المسار المحدد. |
| static boost::filesystem::path [ToBoost](./toboost/)(const [String](../../system/string/)\&) | يرجع مثيلاً لفئة boost::filesystem::path التي تمثل المسار المحدد. |
| static [String](../../system/string/) [ToString](./tostring/)(const boost::filesystem::path\&) | يرجع تمثيلًا نصيًا لكائن المسار المحدد في Boost. |

## الحقول

| Field | Description |
| --- | --- |
| static [AltDirectorySeparatorChar](./altdirectoryseparatorchar/) | حرف بديل يُستخدم لفصل مستويات الدليل في المسار. |
| static [DirectorySeparatorChar](./directoryseparatorchar/) | حرف يُستخدم لفصل مستويات الدليل في المسار. |
| static [PathSeparator](./pathseparator/) | حرف فاصل يُستخدم لفصل سلاسل المسارات في متغيرات البيئة. |
| static [VolumeSeparatorChar](./volumeseparatorchar/) | حرف فاصل الحجم. |

## ملاحظات



```cpp
#include "system/io/path.h"
#include <iostream>

int main()
{
  using namespace System::IO;

  // إنشاء اسم ملف عشوائي.
  auto filename = Path::GetRandomFileName();

  // طباعة معلومات عن اسم الملف.
  std::cout <<
    "Filename: " << Path::GetFileName(filename) << std::endl <<
    "Filename w/o an extension: " << Path::GetFileNameWithoutExtension(filename) << std::endl <<
    "Extension: " << Path::GetExtension(filename) << std::endl;

  return 0;
}
/*
يُنتج مثال الشيفرة التالي الإخراج التالي:
اسم الملف: qhuzkyqv.y6p
اسم الملف بدون امتداد: qhuzkyqv
الامتداد: .y6p
*/
```

## انظر أيضًا

* مساحة الاسم [System::IO](../)
* المكتبة [Aspose.Slides](../../)