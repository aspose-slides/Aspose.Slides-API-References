---
title: ConfigureAwait()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يُهيّئ كيفية تصرف عمليات الانتظار على مهمة النتيجة هذه فيما يتعلق بالتقاط السياق.
type: docs
weight: 27
url: /ar/system.threading.tasks/resulttask/configureawait/
---
## ResultTask::ConfigureAwait(bool) const طريقة

يُهيّئ كيفية تصرف عمليات الانتظار على مهمة النتيجة هذه فيما يتعلق بالتقاط السياق.

```cpp
Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> System::Threading::Tasks::ResultTask<T>::ConfigureAwait(bool continueOnCapturedContext) const
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| continueOnCapturedContext | **bool** | ما إذا كان يجب المتابعة على السياق الملتقط |

### قيمة الإرجاع

Runtime::CompilerServices::ConfiguredResultTaskAwaitable<T> كائن await مكوّن للنتيجة

## ملاحظات

هذا يتيح تحكمًا دقيقًا في تدفق السياق لتقنيات async/await.

## انظر أيضًا

* الفئة [ConfiguredResultTaskAwaitable](../../../system.runtime.compilerservices/configuredresulttaskawaitable/)
* الفئة [ResultTask](../)
* النطاق [System::Threading::Tasks](../../)
* المكتبة [Aspose.Slides](../../../)