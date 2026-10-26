---
title: FileStream()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينشئ مثيلاً جديدًا من فئة FileStream ويُهيئه بالمعلمات المحددة.
type: docs
weight: 1
url: /ar/system.io/filestream/filestream/
---
## FileStream::FileStream(const String\&, FileMode) منشئ


ينشئ مثيلاً جديدًا من الفئة [FileStream](../) ويُهيئه بالمعلمات المحددة.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف المراد فتحه. |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, FileOptions) منشئ


ينشئ مثيلاً جديدًا من الفئة [FileStream](../) ويُهيئه بالمعلمات المحددة.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share=FileShare::Read, int32_t buffer_size=DefaultBufferSize, FileOptions options=FileOptions::SequentialScan)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف المراد فتحه. |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف. |
| access | [FileAccess](../../fileaccess/) | نوع الوصول المطلوب. |
| share | [FileShare](../../fileshare/) | نوع الوصول الذي تملكه كائنات [FileStream](../) الأخرى للملف المفتوح. |
| buffer_size | **int32_t** | عدد البايتات المخزنة مؤقتًا أثناء عمليات القراءة والكتابة. |
| options | [FileOptions](../../fileoptions/) | خيارات إضافية. |

## FileStream::FileStream(const String\&, FileMode, FileAccess, FileShare, int32_t, bool) منشئ


ينشئ مثيلاً جديدًا من الفئة [FileStream](../) ويُهيئه بالمعلمات المحددة.

```cpp
System::IO::FileStream::FileStream(const String &path, FileMode mode, FileAccess access, FileShare share, int32_t buffer_size, bool useAsync)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [String](../../../system/string/)\& | مسار الملف المراد فتحه. |
| mode | [FileMode](../../filemode/) | يحدد الوضع الذي يُفتح به الملف. |
| access | [FileAccess](../../fileaccess/) | نوع الوصول المطلوب. |
| share | [FileShare](../../fileshare/) | نوع الوصول الذي تملكه كائنات [FileStream](../) الأخرى للملف المفتوح. |
| buffer_size | **int32_t** | عدد البايتات المخزنة مؤقتًا أثناء عمليات القراءة والكتابة. |
| useAsync | **bool** | يحدد ما إذا كان سيُستخدم الإدخال/الإخراج غير المتزامن أو المتزامن. |

## ملاحظات



قد لا يدعم نظام التشغيل الأساسي الإدخال/الإخراج غير المتزامن. 

## FileStream::FileStream(const FileStream\&) منشئ




```cpp
System::IO::FileStream::FileStream(const FileStream &)=delete
```

## انظر أيضًا

* Enum [FileMode](../../filemode/)
* Enum [FileAccess](../../fileaccess/)
* Enum [FileShare](../../fileshare/)
* Enum [FileOptions](../../fileoptions/)
* Class [String](../../../system/string/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)