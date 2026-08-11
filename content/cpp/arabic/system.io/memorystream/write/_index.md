---
title: Write()
second_title: مرجع API Aspose.Slides للغة C++
description: يكتب النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى الدفق.
type: docs
weight: 92
url: /ar/system.io/memorystream/write/
---
## MemoryStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى الدفق.

```cpp
void System::IO::MemoryStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## MemoryStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من المصفوفة المحددة إلى الدفق.

```cpp
void System::IO::MemoryStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [MemoryStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)