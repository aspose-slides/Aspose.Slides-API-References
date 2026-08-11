---
title: CopyTo()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينسخ البايتات إلى الدفق المحدد.
type: docs
weight: 209
url: /ar/system.io/stream/copyto/
---
## Stream::CopyTo(const SharedPtr\<Stream\>\&) طريقة

ينسخ البايتات إلى الدفق المحدد.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) التي سيُنسَخ إليها البيانات. |

## Stream::CopyTo(const SharedPtr\<Stream\>\&, int32_t) طريقة

ينسخ البايتات إلى الدفق المحدد باستخدام حجم الذاكرة المؤقتة المحدد.

```cpp
void System::IO::Stream::CopyTo(const SharedPtr<Stream> &destination, int32_t buffer_size)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| destination | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../)\>\& | [Stream](../) التي سيُنسَخ إليها البيانات. |
| buffer_size | **int32_t** | حجم الذاكرة المؤقتة. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)