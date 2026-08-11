---
title: Write()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان وضع التفاف ثنائيًا، يكتب إلى الدفق النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة، وإلا يتم تحويل النطاق الفرعي المحدد من البايتات من مصفوفة البايتات إلى نوع char_type ثم يتم كتابة النتيجة إلى الدفق.
type: docs
weight: 79
url: /ar/system.io/basicstdiostreamwrapper/write/
---
## BasicSTDIOStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

إذا كان وضع التفاف ثنائي، يكتب إلى التدفق النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة، وإلا يقوم بتحويل النطاق الفرعي المحدد من البايتات من مصفوفة البايتات إلى نوع char_type ثم يكتب النتيجة إلى التدفق.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## BasicSTDIOStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايتات المحددة إلى التدفق.

```cpp
virtual void System::IO::BasicSTDIOStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BasicSTDIOStreamWrapper](../)
* مساحة اسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)