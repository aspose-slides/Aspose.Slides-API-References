---
title: Parallel
second_title: Referensi API Aspose.Slides untuk C++
description: Menyediakan dukungan untuk loop paralel dan wilayah.
type: docs
weight: 1
url: /id/system.threading.tasks/parallel/
---
## Kelas Parallel

Menyediakan dukungan untuk loop paralel dan wilayah.

```cpp
class Parallel
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[ParallelOptions](../paralleloptions/)\>\&, const [Action](../../system/action/)\<TSource\>\&) | Menjalankan operasi foreach pada IEnumerable di mana iterasi dapat dijalankan secara paralel. |
| static [ParallelLoopResult](../parallelloopresult/) [ForEach](./foreach/)(const [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<TSource\>\>\&, const [Action](../../system/action/)\<TSource\>\&) | Menjalankan operasi foreach pada IEnumerable di mana iterasi dapat dijalankan secara paralel. |

## Catatan

Kelas ini menyediakan metode untuk eksekusi paralel dari loop dan operasi.

## Lihat Juga

* Ruang Nama [System::Threading::Tasks](../)
* Perpustakaan [Aspose.Slides](../../)