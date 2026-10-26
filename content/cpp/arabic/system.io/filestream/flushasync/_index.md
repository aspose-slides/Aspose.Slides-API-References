---
title: FlushAsync()
second_title: مرجع Aspose.Slides للغة C++ API
description: يفرغ بشكل غير متزامن جميع المخازن المؤقتة لهذا التدفق، ويتسبب في كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء.
type: docs
weight: 157
url: /ar/system.io/filestream/flushasync/
---
## طريقة FileStream::FlushAsync(const Threading::CancellationToken\&) method

يفرغ بشكل غير متزامن جميع المخازن المؤقتة لهذا التدفق، ويؤدي إلى كتابة أي بيانات مخزنة مؤقتًا إلى الجهاز الأساسي، ويراقب طلبات الإلغاء.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز المميز لمراقبة طلبات الإلغاء. |

### قيمة الإرجاع

مهمة تمثل عملية التفريغ غير المتزامنة.

## انظر أيضًا

* تعريف نوع [TaskPtr](../../../system/taskptr/)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [FileStream](../)
* مساحة الأسماء [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)