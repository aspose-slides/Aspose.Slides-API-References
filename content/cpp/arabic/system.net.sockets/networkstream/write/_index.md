---
title: Write()
second_title: Aspose.Slides لمرجع API للغة C++
description: يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى الدفق.
type: docs
weight: 209
url: /ar/system.net.sockets/networkstream/write/
---
## NetworkStream::Write(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى الدفق.

```cpp
void System::Net::Sockets::NetworkStream::Write(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة. |
| offset | **int32_t** | الإزاحة بالبايتات في المصفوفة المحددة. |
| size | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |

## NetworkStream::Write(const System::Details::ArrayView\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب النطاق الفرعي المحدد من البايتات من مصفوفة البايت المحددة إلى الدفق.

```cpp
void System::Net::Sockets::NetworkStream::Write(const System::Details::ArrayView<uint8_t> &buffer, int32_t offset, int32_t size) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | const System::Details::ArrayView\<**uint8_t**\>\& | عرض المصفوفة الذي يحتوي على البايتات للكتابة |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** الذي يبدأ منه النطاق الفرعي للكتابة |
| size | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة |

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)