---
title: ForEach()
second_title: Aspose.Slides için C++ API Referansı
description: İterasyonların paralel olarak çalışabileceği bir IEnumerable üzerinde foreach işlemi gerçekleştirir.
type: docs
weight: 1
url: /tr/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) metot

Bir IEnumerable üzerinde yinelemeler paralel olarak çalışabilecek bir foreach işlemi gerçekleştirir.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSource | Kaynağındaki verinin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Yinelemeli bir veri kaynağı. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | Bu işlemin davranışını yapılandıran bir nesne. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Her yinelemede bir kez çağrılan delege. |

### Dönüş Değeri

[ParallelLoopResult](../../parallelloopresult/) yapısı, döngünün hangi kısmının tamamlandığına dair bilgi içerir.

## Açıklamalar

Bu metot, kaynak enumerable'ı bölerek body delege'sini birden fazla iş parçacığında eşzamanlı olarak çalıştırır.

## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) metot

Bir IEnumerable üzerinde yinelemeler paralel olarak çalışabilecek bir foreach işlemi gerçekleştirir.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| TSource | Kaynağındaki verinin türü. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | Yinelemeli bir veri kaynağı. |
| body | const [Action](../../../system/action/)\<TSource\>\& | Her yinelemede bir kez çağrılan delege. |

### Dönüş Değeri

[ParallelLoopResult](../../parallelloopresult/) yapısı, döngünün hangi kısmının tamamlandığına dair bilgi içerir.

## Açıklamalar

Sınırsız paralellik ve iptal olmadan varsayılan [ParallelOptions](../../paralleloptions/)'yi kullanır.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Class [ParallelLoopResult](../../parallelloopresult/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Class [ParallelOptions](../../paralleloptions/)
* Class [Parallel](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)