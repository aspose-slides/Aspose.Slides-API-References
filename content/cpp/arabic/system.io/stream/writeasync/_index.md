---
title: WriteAsync()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يكتب بشكل غير متزامن تسلسلاً من البايتات إلى الدفق الحالي، ويُحرك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء.
type: docs
weight: 66
url: /ar/system.io/stream/writeasync/
---
## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) طريقة

يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويُحرك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء.

```cpp
virtual TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء. |

### قيمة الإرجاع

مهمة تمثل عملية الكتابة غير المتزامنة.

## Stream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) طريقة

يكتب بشكل غير متزامن تسلسلًا من البايتات إلى الدفق الحالي، ويُحرك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء.

```cpp
TaskPtr System::IO::Stream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات للكتابة. |
| offset | **int32_t** | فهرس يبدأ من الصفر للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |

### قيمة الإرجاع

مهمة تمثل عملية الكتابة غير المتزامنة.

## انظر أيضًا

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [Stream](../)
* مساحة الاسم [System::IO](../../)
* Library [Aspose.Slides](../../../)