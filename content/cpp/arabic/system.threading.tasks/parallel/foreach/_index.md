---
title: ForEach()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: ينفّذ عملية foreach على IEnumerable حيث يمكن أن تُجرى التكرارات بشكل متوازي.
type: docs
weight: 1
url: /ar/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) طريقة


ينفّذ عملية foreach على IEnumerable يمكن أن تجري فيها التكرارات بشكل متوازي.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSource | نوع البيانات في المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | مصدر بيانات قابل للتعداد. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | كائن يكوّن سلوك هذه العملية. |
| body | const [Action](../../../system/action/)\<TSource\>\& | المفوض الذي يُستدعى مرة واحدة لكل تكرار. |

### قيمة الإرجاع

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## ملاحظات



تقسّم هذه الطريقة المصدر القابل للتعداد وتنفّذ مندوب الجسم على عدة خيوط بشكل متزامن. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) طريقة


ينفّذ عملية foreach على IEnumerable يمكن أن تجري فيها التكرارات بشكل متوازي.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### معلمات القالب

| المعامل | الوصف |
| --- | --- |
| TSource | نوع البيانات في المصدر. |

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | مصدر بيانات قابل للتعداد. |
| body | const [Action](../../../system/action/)\<TSource\>\& | المفوض الذي يُستدعى مرة واحدة لكل تكرار. |

### قيمة الإرجاع

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## ملاحظات



يستخدم [ParallelOptions](../../paralleloptions/) الافتراضي مع توازي غير محدود ولا إلغاء. 
## انظر أيضا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [ParallelLoopResult](../../parallelloopresult/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)