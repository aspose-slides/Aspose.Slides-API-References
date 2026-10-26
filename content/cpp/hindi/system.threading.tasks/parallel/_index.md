---
title: Parallel
second_title: Aspose.Slides for C++ API संदर्भ
description: समानांतर लूप और क्षेत्रों के लिए समर्थन प्रदान करता है।
type: docs
weight: 1
url: /hi/system.threading.tasks/parallel/
---
## Parallel क्लास

समानांतर लूप और क्षेत्रों के लिए समर्थन प्रदान करता है।

```cpp
class Parallel
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executes a foreach operation on an IEnumerable in which iterations may run in parallel. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Executes a foreach operation on an IEnumerable in which iterations may run in parallel. |

## टिप्पणियाँ

यह क्लास लूप और ऑपरेशनों के समानांतर निष्पादन के लिए मेथड्स प्रदान करती है। 

## देखें

* नामस्थान [System::Threading::Tasks](../)
* लाइब्रेरी [Aspose.Slides](../../)