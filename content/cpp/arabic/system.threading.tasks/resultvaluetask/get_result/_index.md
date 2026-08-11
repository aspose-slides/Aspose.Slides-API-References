---
title: get_Result()
second_title: Aspose.Slides للـ C++ مرجع API
description: يسترجع نتيجة المهمة المكتملة.
type: docs
weight: 66
url: /ar/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result() طريقة

يسترجع نتيجة المهمة المكتملة.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```

### قيمة الإرجاع

T قيمة النتيجة.

## ملاحظات

إذا كانت المهمة مدعومة بـ ResultTask<T>، ستقوم هذه الطريقة بانتظار النتيجة وتخزينها مؤقتًا. ستعيد الاستدعاءات اللاحقة القيمة المخزنة مؤقتًا دون انتظار.

## انظر أيضًا

* الفئة [ResultValueTask](../)
* المجال [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)