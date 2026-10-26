---
title: UnmanagedMemoryStream()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ مثيلًا جديدًا من UnmanagedMemoryStream.
type: docs
weight: 118
url: /ar/system.io/unmanagedmemorystream/unmanagedmemorystream/
---
## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t) منشئ

ينشئ مثيلاً جديدًا لـ [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pointer | **uint8_t** * | مؤشر إلى ذاكرة غير مُدارة |
| length | **int64_t** | حجم الذاكرة غير المُدارة بالبايت |

## UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *, int64_t, int64_t, FileAccess) منشئ

ينشئ مثيلاً جديدًا لـ [UnmanagedMemoryStream](../).

```cpp
System::IO::UnmanagedMemoryStream::UnmanagedMemoryStream(uint8_t *pointer, int64_t length, int64_t capacity, FileAccess access)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pointer | **uint8_t** * | مؤشر إلى ذاكرة غير مُدارة |
| length | **int64_t** | حجم الذاكرة غير المُدارة بالبايت |
| capacity | **int64_t** | إجمالي مساحة الذاكرة المخصصة للتدفق |
| access | [FileAccess](../../fileaccess/) | يحدد ما إذا كان التدفق للقراءة فقط أو للكتابة فقط أو كليهما |

## انظر أيضًا

* تعداد [FileAccess](../../fileaccess/)
* فئة [UnmanagedMemoryStream](../)
* فضاء أسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)