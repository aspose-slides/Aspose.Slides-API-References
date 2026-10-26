---
title: Replace()
second_title: دليل API Aspose.Slides للغة C++
description: يستبدل محتوى ملف بآخر وينشئ نسخة احتياطية من الملف المستبدل.
type: docs
weight: 339
url: /ar/system.io/file/replace/
---
## File::Replace(const String\&, const String\&, const String\&, bool) method

يستبدل محتويات ملف بآخر ويُنشئ نسخة احتياطية من الملف المستبدل.

```cpp
static void System::IO::File::Replace(const String &sourceFileName, const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors=1)
```

### المعاملات

| معامل | النوع | الوصف |
| --- | --- | --- |
| sourceFileName | const [String](../../../system/string/)\& | اسم الملف الذي سيتم الاستبدال به |
| destinationFileName | const [String](../../../system/string/)\& | اسم الملف الذي سيتم استبداله |
| destinationBackupFileName | const [String](../../../system/string/)\& | اسم ملف النسخة الاحتياطية |
| ignoreMetadataErrors | **bool** | يحدد ما إذا كان ينبغي تجاهل أخطاء الدمج من الملف المستبدل إلى ملف الاستبدال (true) أم لا (false) |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [File](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)