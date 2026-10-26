---
title: MakeYieldEnumerator()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat IEnumerator dari fungsi yield.
type: docs
weight: 2432
url: /id/system/makeyieldenumerator/
---
## System::MakeYieldEnumerator(const Details::YieldFunction\<T\>\&) fungsi

Creates an IEnumerator from a yield function.

```cpp
template<typename T> SharedPtr<Collections::Generic::IEnumerator<T>> System::MakeYieldEnumerator(const Details::YieldFunction<T> &fnc)
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

Shared pointer ke IEnumerator

## Lihat Juga

* Typedef [SharedPtr](../sharedptr/)
* Kelas [IEnumerator](../../system.collections.generic/ienumerator/)
* Ruang Nama [System](../)
* Perpustakaan [Aspose.Slides](../../)