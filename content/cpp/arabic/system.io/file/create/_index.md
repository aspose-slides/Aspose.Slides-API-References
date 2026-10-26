---
title: Create()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ ملفًا جديدًا (أو يكتب فوق الملف الموجود) ويفتحه للوصول للقراءة والكتابة باستخدام حجم المخزن المؤقت المحدد والخيارات.
type: docs
weight: 53
url: /ar/system.io/file/create/
---
## File::Create(const String\&, int32_t, FileOptions) method


ينشئ ملفًا جديدًا (أو يكتب فوق الملف الموجود) ويفتحه للوصول للقراءة والكتابة باستخدام حجم المخزن المؤقت المحدد والخيارات.

```cpp
static FileStreamPtr System::IO::File::Create(const String &path, int32_t bufferSize=DefaultBufferSize, FileOptions options=FileOptions::None)
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف لإنشائه أو الكتابة فوقه |
| bufferSize | **int32_t** | عدد البايتات المخزنة مؤقتًا أثناء القراءة من الملف والكتابة إليه |
| options | [FileOptions](../../fileoptions/) |حدد كيفية إنشاء أو كتابة الملف فوقه |

### قيمة الإرجاع

مؤشر مشترك إلى كائن [FileStream](../../filestream/) المرتبط بالملف المحدد

## انظر أيضًا

* Enum [FileOptions](../../fileoptions/)
* Typedef [FileStreamPtr](../../../system/filestreamptr/)
* Class [String](../../../system/string/)
* Class [File](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)