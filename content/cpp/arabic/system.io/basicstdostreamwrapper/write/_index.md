---
title: Write()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: إذا كان وضع الالتفاف ثنائيًا، يكتب إلى التدفق الجزء المحدد من البايتات من المصفوفة البايتية المحددة، وإلا يحول الجزء المحدد من البايتات من المصفوفة البايتية المحددة إلى نوع char_type ثم يكتب النتيجة إلى التدفق.
type: docs
weight: 79
url: /ar/system.io/basicstdostreamwrapper/write/
---
## BasicSTDOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

إذا كان وضع الالتفاف ثنائيًا، يكتب إلى التدفق الجزء المحدد من البايتات من المصفوفة البايتية المحددة، وإلا يحول الجزء المحدد من البايتات من المصفوفة البايتية المحددة إلى نوع char_type ثم يكتب النتيجة إلى التدفق.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| معمل | نوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ الجزء المراد كتابته |
| count | **int32_t** | عدد العناصر في الجزء المراد كتابته |

## BasicSTDOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب الجزء المحدد من البايتات من المصفوفة البايتية المحددة إلى التدفق.

```cpp
virtual void System::IO::BasicSTDOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعاملات

| معمل | نوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ الجزء المراد كتابته |
| count | **int32_t** | عدد العناصر في الجزء المراد كتابته |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BasicSTDOStreamWrapper](../)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)