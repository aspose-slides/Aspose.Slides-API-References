---
title: ForEach()
second_title: Referensi API Aspose.Slides untuk C++
description: Menjalankan operasi foreach pada IEnumerable di mana iterasi dapat dijalankan secara paralel.
type: docs
weight: 1
url: /id/system.threading.tasks/parallel/foreach/
---
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const SharedPtr\<ParallelOptions\>\&, const Action\<TSource\>\&) metode

Menjalankan operasi foreach pada IEnumerable di mana iterasi dapat dijalankan secara paralel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const SharedPtr<ParallelOptions> &parallelOptions, const Action<TSource> &body)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| parallelOptions | const [SharedPtr](../../../system/sharedptr/)\<[ParallelOptions](../../paralleloptions/)\>\& | An object that configures the behavior of this operation. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Nilai Kembali

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Catatan



Metode ini membagi enumerable sumber dan menjalankan delegasi body pada beberapa thread secara bersamaan. 
## Parallel::ForEach(const SharedPtr\<Collections::Generic::IEnumerable\<TSource\>\>\&, const Action\<TSource\>\&) metode


Menjalankan operasi foreach pada IEnumerable di mana iterasi dapat dijalankan secara paralel.

```cpp
template<typename TSource> static ParallelLoopResult System::Threading::Tasks::Parallel::ForEach(const SharedPtr<Collections::Generic::IEnumerable<TSource>> &source, const Action<TSource> &body)
```


### Parameter templat

| Parameter | Description |
| --- | --- |
| TSource | The type of the data in the source. |

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| source | const [SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<TSource\>\>\& | An enumerable data source. |
| body | const [Action](../../../system/action/)\<TSource\>\& | The delegate that is invoked once per iteration. |

### Nilai Kembali

A [ParallelLoopResult](../../parallelloopresult/) structure that contains information on what portion of the loop completed.
## Catatan



Menggunakan [ParallelOptions](../../paralleloptions/) default dengan paralelisme tak terbatas dan tanpa pembatalan. 
## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [Action](../../../system/action/)
* Kelas [ParallelLoopResult](../../parallelloopresult/)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [ParallelOptions](../../paralleloptions/)
* Kelas [Parallel](../)
* Ruang Nama [System::Threading::Tasks](../../)
* Library [Aspose.Slides](../../../)