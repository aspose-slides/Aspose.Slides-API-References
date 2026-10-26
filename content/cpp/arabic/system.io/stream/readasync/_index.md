---
title: ReadAsync()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يقرأ بشكل غير متزامن تسلسلًا من البايتات من التيار الحالي، ويتقدم بالموقع داخل التيار بعدد البايتات المقروءة، ويراقب طلبات الإلغاء.
type: docs
weight: 40
url: /ar/system.io/stream/readasync/
---
## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t, const Threading::CancellationToken\&) method

يقرأ بشكل غير متزامن تسلسلًا من البايتات من التيار الحالي، ويتقدم بالموقع داخل التيار بعدد البايتات المقروءة، ويراقب طلبات الإلغاء.

```cpp
virtual RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة البايتية التي تُكتب إليها البايتات المقروءة. |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة فيه. |
| count | **int32_t** | عدد البايتات التي سيتم قراءتها. |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء. |

### القيمة المرجعة

مهمة تمثل عملية القراءة غير المتزامنة. يحتوي قيمة المعامل TResult على إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد تكون قيمة النتيجة أقل من عدد البايتات المطلوبة إذا كان عدد البايتات المتاحة حالياً أقل من العدد المطلوب، أو قد تكون 0 (صفر) إذا تم الوصول إلى نهاية التيار.

## Stream::ReadAsync(const ArrayPtr\<uint8_t\>\&, int32_t, int32_t) method

يقرأ بشكل غير متزامن تسلسلًا من البايتات من التيار الحالي، ويتقدم بالموقع داخل التيار بعدد البايتات المقروءة، ويراقب طلبات الإلغاء.

```cpp
RTaskPtr<int32_t> System::IO::Stream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | المصفوفة البايتية التي تُكتب إليها البايتات المقروءة. |
| offset | **int32_t** | موضع يبدأ من الصفر في **buffer** للبدء بالكتابة فيه. |
| count | **int32_t** | عدد البايتات التي سيتم قراءتها. |

### القيمة المرجعة

مهمة تمثل عملية القراءة غير المتزامنة. يحتوي قيمة المعامل TResult على إجمالي عدد البايتات المقروءة إلى المخزن المؤقت. قد تكون قيمة النتيجة أقل من عدد البايتات المطلوبة إذا كان عدد البايتات المتاحة حالياً أقل من العدد المطلوب، أو قد تكون 0 (صفر) إذا تم الوصول إلى نهاية التيار.

## انظر أيضاً

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)