---
title: CheckPath()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يحدد ما إذا كان المسار المحدد صالحًا عن طريق التحقق مما إذا كان يحتوي على أحرف غير صالحة. يتم رمي استثناء إذا كان المسار يحتوي على أحرف غير صالحة.
type: docs
weight: 209
url: /ar/system.io/path/checkpath/
---
## Path::CheckPath(const String\&, const String\&, bool) طريقة

يُحدِّد ما إذا كان المسار المحدد صالحًا عن طريق التحقق مما إذا كان يحتوي على أحرف غير صالحة. يتم رمي استثناء إذا كان المسار يحتوي على أحرف غير صالحة.

```cpp
static void System::IO::Path::CheckPath(const String &path, const String &msg=s_msg_path, bool allow_empty=1)
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | المسار للتحقق منه |
| msg | const [String](../../../system/string/)\& | الرسالة لتمريرها إلى مُنشئ كائن الاستثناء |
| allow_empty | **bool** | يحدد ما إذا كان ينبغي اعتبار سلسلة فارغة أو null مسارًا صحيحًا (true) أم لا (false)؛ إذا كان هذا المعامل false وكان **path** فارغًا يتم رمي ArgumentException؛ إذا كان هذا المعامل false وكان **path** null يتم رمي ArgumentNullException |

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [Path](../)
* النطاق [System::IO](../../)
* المكتبة [Aspose.Slides](../../../)