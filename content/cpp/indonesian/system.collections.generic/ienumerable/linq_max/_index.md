---
title: LINQ_Max()
second_title: Referensi API Aspose.Slides untuk C++
description: Memanggil fungsi transformasi pada setiap elemen dari urutan generik dan mengembalikan nilai maksimum yang dihasilkan.
type: docs
weight: 352
url: /id/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metode


Memanggil fungsi transformasi pada setiap elemen dari urutan generik dan mengembalikan nilai maksimum yang dihasilkan.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh selector. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Fungsi transformasi yang diterapkan pada setiap elemen. |

### Nilai Kembali

Nilai maksimum dalam urutan.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metode




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Lihat Juga

* Kelas [Func](../../../system/func/)
* Kelas [IEnumerable](../)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)