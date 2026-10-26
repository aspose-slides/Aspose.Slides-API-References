---
title: LINQ_Average()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghitung rata-rata dari sekumpulan nilai numerik.
type: docs
weight: 365
url: /id/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() metode

Menghitung rata-rata dari sekumpulan nilai numerik.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### Nilai Kembali

Rata-rata nilai dalam sekumpulan.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) metode

Menghitung rata-rata dari sekumpulan nilai yang diperoleh dengan memanggil fungsi transformasi pada setiap elemen dari sekumpulan masukan.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### Parameter Templat

| Parameter | Description |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh selector. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Fungsi transformasi yang diterapkan pada setiap elemen. |

### Nilai Kembali

Rata-rata nilai yang diproyeksikan.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) metode

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Lihat Juga

* Kelas [IEnumerable](../)
* Kelas [Func](../../../system/func/)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)