---
title: Parallel
second_title: Aspose.Slides for C++ API Referansı
description: Paralel döngüler ve bölgeler için destek sağlar.
type: docs
weight: 1
url: /tr/system.threading.tasks/parallel/
---
## Parallel sınıfı


Provides support for parallel loops and regions.

```cpp
class Parallel
```

## Metotlar

| Metot | Açıklama |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | İterasyonların paralel olarak çalışabileceği bir IEnumerable üzerinde foreach işlemi yürütür. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | İterasyonların paralel olarak çalışabileceği bir IEnumerable üzerinde foreach işlemi yürütür. |
## Açıklamalar


Bu sınıf döngülerin ve işlemlerin paralel yürütülmesi için metotlar sağlar. 
## Ayrıca Bakınız

* Ad alanı [System::Threading::Tasks](../)
* Kütüphane [Aspose.Slides](../../)