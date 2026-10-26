---
title: Write()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إذا كان وضع الالتفاف ثنائيًا، يكتب إلى التدفق الجزء الفرعي المحدد من البايتات من مصفوفة البايت المحددة، وإلا يحول الجزء الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى نوع char_type ثم يكتب النتيجة إلى التدفق. غير مدعوم!
type: docs
weight: 79
url: /ar/system.io/basicstdistreamwrapper/write/
---
## BasicSTDIStreamWrapper::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

إذا كان وضع الالتفاف ثنائيًا، يكتب إلى التدفق الجزء الفرعي المحدد من البايتات من مصفوفة البايت المحددة، وإلا يحول الجزء الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى نوع char_type ثم يكتب النتيجة إلى التدفق. غير مدعوم!

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يُبدأ من الصفر للعنصر في **buffer** الذي يبدأ عنده الجزء الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في الجزء الفرعي للكتابة. |

## BasicSTDIStreamWrapper::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) method

يكتب الجزء الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى التدفق.

```cpp
virtual void System::IO::BasicSTDIStreamWrapper<T, typename>::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t count) override
```

### الوسائط

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يُبدأ من الصفر للعنصر في **buffer** الذي يبدأ عنده الجزء الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في الجزء الفرعي للكتابة. |

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [BasicSTDIStreamWrapper](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)