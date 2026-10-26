---
title: AsTask()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحوّل هذا ResultValueTask إلى مؤشر مشترك إلى ResultTask<T>.
type: docs
weight: 79
url: /ar/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask() const طريقة

يقوم بتحويل هذا [ResultValueTask](../) إلى مؤشر مشترك إلى ResultTask<T>.

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```

### قيمة الإرجاع

RTaskPtr<T> مؤشر مشترك إلى ResultTask<T> يمثل هذه العملية.
## ملاحظات

إذا كان الـ [ResultValueTask](../) يحتوي على نتيجة مباشرة، يُنشئ مهمة مكتملة بهذه النتيجة. إذا كان يحتوي على مهمة، يرجع مؤشرًا مشتركًا إلى تلك المهمة.

## انظر أيضًا

* تعريف [RTaskPtr](../../../system/rtaskptr/)
* صف [ResultValueTask](../)
* نطاق [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)