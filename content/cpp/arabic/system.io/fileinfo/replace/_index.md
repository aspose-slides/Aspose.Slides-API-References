---
title: Replace()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يستبدل محتويات ملف وجهة محدد بالملف الممثل بواسطة كائن FileInfo الحالي وينشئ نسخة احتياطية من الملف المستبدل.
type: docs
weight: 131
url: /ar/system.io/fileinfo/replace/
---
## FileInfo::Replace(const String\&, const String\&) طريقة

يستبدل محتويات ملف وجهة محدد بالملف الممثل بواسطة كائن [FileInfo](../) الحالي وينشئ نسخة احتياطية من الملف المستبدل.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | اسم الملف الذي سيتم استبداله |
| destinationBackupFileName | const [String](../../../system/string/)\& | اسم ملف النسخة الاحتياطية |

### قيمة الإرجاع

كائن FileInfor يمثل الملف المشار إليه بواسطة **destinationFileName**

## FileInfo::Replace(const String\&, const String\&, bool) طريقة

يستبدل محتويات ملف وجهة محدد بالملف الممثل بواسطة كائن [FileInfo](../) الحالي وينشئ نسخة احتياطية من الملف المستبدل.

```cpp
FileInfoPtr System::IO::FileInfo::Replace(const String &destinationFileName, const String &destinationBackupFileName, bool ignoreMetadataErrors)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| destinationFileName | const [String](../../../system/string/)\& | اسم الملف الذي سيتم استبداله |
| destinationBackupFileName | const [String](../../../system/string/)\& | اسم ملف النسخة الاحتياطية |
| ignoreMetadataErrors | **bool** | يحدد ما إذا كان يجب تجاهل أخطاء الدمج من الملف المستبدل إلى ملف الاستبدال (true) أو لا (false) |

### قيمة الإرجاع

كائن FileInfor يمثل الملف المشار إليه بواسطة **destinationFileName**

## انظر أيضًا

* Typedef [FileInfoPtr](../../../system/fileinfoptr/)
* Class [String](../../../system/string/)
* Class [FileInfo](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)