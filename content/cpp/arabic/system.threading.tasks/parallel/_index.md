---
title: Parallel
second_title: مرجع API Aspose.Slides للـ C++
description: يوفر دعماً للحلقات المتوازية والمناطق.
type: docs
weight: 1
url: /ar/system.threading.tasks/parallel/
---
## Parallel فئة

يوفر دعماً للحلقات المتوازية والمناطق.

```cpp
class Parallel
```

## الطرق

| طريقة | وصف |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | ينفّذ عملية foreach على IEnumerable يمكن أن تجري فيها التكرارات بالتوازي. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | ينفّذ عملية foreach على IEnumerable يمكن أن تجري فيها التكرارات بالتوازي. |
## ملاحظات

توفر هذه الفئة طرقاً لتنفيذ الحلقات والعمليات بالتوازي. 
## انظر أيضًا

* مساحة اسم [System::Threading::Tasks](../)
* مكتبة [Aspose.Slides](../../)