---
title: ReadAsync()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يقوم بقراءة تسلسل من البايتات من الدفق الحالي بشكل غير متزامن، ويُحرك المؤشر داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء.
type: docs
weight: 196
url: /ar/system.io/filestream/readasync/
---
## FileStream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) طريقة

يقوم بقراءة تسلسل من البايتات من الدفق الحالي بشكل غير متزامن، ويُحرك المؤشر داخل الدفق بعدد البايتات المقروءة، ويراقب طلبات الإلغاء.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```

### المعلمات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | مصفوفة البايتات التي ستُكتب فيها البايتات المقروءة. |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** لبدء الكتابة. |
| count | **int32_t** | عدد البايتات التي ستُقرأ. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء. |

### قيمة الإرجاع

مهمة تمثل عملية القراءة غير المتزامنة. تحتوي قيمة معلمة TResult على إجمالي عدد البايتات المقروءة داخل المخزن المؤقت. قد تكون قيمة النتيجة أقل من عدد البايتات المطلوبة إذا كان عدد البايتات المتاحة حاليًا أقل من العدد المطلوب، أو قد تكون 0 (صفر) إذا تم الوصول إلى نهاية الدفق.

## أنظر أيضا

* تعريف نوع [RTaskPtr](../../../system/rtaskptr/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [FileStream](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)