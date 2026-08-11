---
title: WriteAsync()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يكتب بشكل غير متزامن تسلسلاً من البايتات إلى الدفق الحالي، ويُحَرِّك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء.
type: docs
weight: 261
url: /ar/system.io/filestream/writeasync/
---
## FileStream::WriteAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) طريقة

يكتب بشكل غير متزامن تسلسلاً من البايتات إلى الدفق الحالي، ويُحَرِّك الموضع الحالي داخل هذا الدفق بعدد البايتات المكتوبة، ويراقب طلبات الإلغاء.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة التي تحتوي على البايتات المراد كتابتها. |
| offset | **int32_t** | فهرس بدائي يبدأ من 0 للعنصر في **buffer** حيث يبدأ النطاق الفرعي للكتابة. |
| count | **int32_t** | عدد العناصر في النطاق الفرعي للكتابة. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء. |

### قيمة الإرجاع

مهمة تمثل عملية الكتابة غير المتزامنة.

## انظر أيضًا

* تعريف نوع [TaskPtr](../../../system/taskptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [FileStream](../)
* مساحة الأسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)