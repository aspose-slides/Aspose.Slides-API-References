---
title: FlushAsync()
second_title: مرجع API لـ Aspose.Slides لـ C++
description: يقوم بشكل غير متزامن بمسح جميع المخازن المؤقتة لهذا الدفق، ويتسبب في كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء.
type: docs
weight: 118
url: /ar/system.io/stream/flushasync/
---
## Stream::FlushAsync(const Threading::CancellationToken\&) طريقة

يقوم بشكل غير متزامن بمسح جميع المخازن المؤقتة لهذا الدفق، ويتسبب في كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| cancellationToken | const [Threading::CancellationToken](../../../system.threading/cancellationtoken/)\& | الرمز لمراقبة طلبات الإلغاء. |

### قيمة الإرجاع

مهمة تمثل عملية التفريغ غير المتزامنة.

## Stream::FlushAsync() طريقة

يقوم بشكل غير متزامن بمسح جميع المخازن المؤقتة لهذا الدفق، ويتسبب في كتابة أي بيانات مخزنة إلى الجهاز الأساسي، ويراقب طلبات الإلغاء.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```

### قيمة الإرجاع

مهمة تمثل عملية التفريغ غير المتزامنة.

## راجع أيضًا

* تعريف نوع [TaskPtr](../../../system/taskptr/)
* فئة [CancellationToken](../../../system.threading/cancellationtoken/)
* فئة [Stream](../)
* مساحة الاسم [System::IO](../../)
* مكتبة [Aspose.Slides](../../../)