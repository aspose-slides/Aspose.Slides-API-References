---
title: ConfigureAwait()
second_title: Aspose.Slides لـ C++ مرجع API
description: يضبط awaiter لهذه المهمة.
type: docs
weight: 92
url: /ar/system.threading.tasks/resultvaluetask/configureawait/
---
## ResultValueTask::ConfigureAwait(bool) const طريقة

يضبط awaiter لهذه المهمة.

```cpp
Runtime::CompilerServices::ConfiguredResultValueTaskAwaitable<T> System::Threading::Tasks::ResultValueTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | true لمحاولة نقل الاستمرار إلى السياق الأصلي الذي تم التقاطه؛ وإلا، false. |

### قيمة الإرجاع

ConfiguredResultValueTaskAwaitable<T> كائن يكوّن كيفية تصرف awaiters لهذه المهمة.

## انظر أيضًا

* الفئة [ConfiguredResultValueTaskAwaitable](../../../system.runtime.compilerservices/configuredresultvaluetaskawaitable/)
* الفئة [ResultValueTask](../)
* مساحة الأسماء [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)