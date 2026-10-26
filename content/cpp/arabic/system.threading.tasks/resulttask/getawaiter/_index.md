---
title: GetAwaiter()
second_title: Aspose.Slides للغة C++ مرجع API
description: يحصل على awaiter لهذه مهمة النتيجة للاستخدام مع Await.
type: docs
weight: 53
url: /ar/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter() const طريقة

يحصل على awaiter لهذه المهمة النتيجة لاستخدامه مع Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```

### قيمة الإرجاع

Runtime::CompilerServices::ResultTaskAwaiter<T> كائن awaiter يُعيد النتيجة

## ملاحظات

عند الانتظار، سيستأنف الـ coroutine عندما تكون قيمة النتيجة متاحة

## انظر أيضًا

* فئة [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* فئة [ResultTask](../)
* نطاق [System::Threading::Tasks](../../)
* مكتبة [Aspose.Slides](../../../)