---
title: Read()
second_title: مرجع API ل Aspose.Slides للغة C++
description: يقوم بقراءة عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة.
type: docs
weight: 183
url: /ar/system.io/filestream/read/
---
## FileStream::Read(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق ويكتبها إلى مصفوفة البايتات المحددة.

```cpp
int32_t System::IO::FileStream::Read(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| معلمة | نوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايت التي تُكتب فيها البايتات المقروءة. |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة. |
| count | **int32_t** | عدد البايتات التي سيتم قراؤها. |

### قيمة الإرجاع

عدد البايتات المقروءة.

## FileStream::Read(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يقوم بقراءة عدد البايتات المحدد من الدفق ويكتبها إلى عرض مصفوفة البايتات المحددة.

```cpp
int32_t System::IO::FileStream::Read(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| معلمة | نوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض مصفوفة البايت التي تُكتب فيها البايتات المقروءة. |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة. |
| count | **int32_t** | عدد البايتات التي سيتم قراؤها. |

### قيمة الإرجاع

عدد البايتات المقروءة.

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)