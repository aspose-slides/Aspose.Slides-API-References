---
title: Write()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى الدفق.
type: docs
weight: 53
url: /ar/system.io/stream/write/
---
## Stream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى الدفق.

```cpp
virtual void System::IO::Stream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس 0----- للعنصر في **buffer** الذي يبدأ منه النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## Stream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من عرض المصفوفة المحدد إلى الدفق.

```cpp
virtual void System::IO::Stream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس 0----- للعنصر في **buffer** الذي يبدأ منه النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## Stream::Write(const System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى الدفق.

```cpp
template<std::size_t> void System::IO::Stream::Write(const System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t count)
```

### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| N | حجم مصفوفة المكدس |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة المكدس التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس 0----- للعنصر في **buffer** الذي يبدأ منه النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## Stream::Write(const System::ReadOnlySpan\<uint8_t\>\&) طريقة

يكتب النطاق الفرعي المحدد من البايتات من نطاق البايت المحدد إلى الدفق.

```cpp
virtual void System::IO::Stream::Write(const System::ReadOnlySpan<uint8_t> &buffer)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [System::ReadOnlySpan](../../../system/readonlyspan/)\<**uint8_t**\>\& | نطاق البايتات لقراءة البايتات المكتوبة منه |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [Stream](../)
* فئة [ReadOnlySpan](../../../system/readonlyspan/)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)