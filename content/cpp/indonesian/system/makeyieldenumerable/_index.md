---
title: MakeYieldEnumerable()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat IEnumerable dari fungsi yield.
type: docs
weight: 2419
url: /id/system/makeyieldenumerable/
---
## System::MakeYieldEnumerable(const Details::YieldFunction\<T\>\&) fungsi

Membuat IEnumerable dari fungsi yield.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerable<T>> System::MakeYieldEnumerable(const Details::YieldFunction<T> &fnc)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| T | Tipe elemen dalam urutan |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fnc | const Details::YieldFunction\<T\>\& | Fungsi yield yang akan dijalankan |

### Nilai Kembali

Pointer bersama ke IEnumerable

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Kelas [IEnumerable](../../system.collections.generic/ienumerable/)
* Ruang Nama [System](../)
* Library [Aspose.Slides](../../)