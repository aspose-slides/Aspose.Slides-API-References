---
title: LINQ_Min()
second_title: Referensi API Aspose.Slides untuk C++
description: Memanggil fungsi transformasi pada setiap elemen dalam urutan generik dan mengembalikan nilai minimum yang dihasilkan.
type: docs
weight: 339
url: /id/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metode

Memanggil fungsi transformasi pada setiap elemen dari urutan generik dan mengembalikan nilai minimum yang dihasilkan.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh selector. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Fungsi transformasi yang diterapkan pada setiap elemen. |

### Nilai Kembalian

Nilai minimum dalam urutan.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metode

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Lihat Juga

* Kelas [Func](../../../system/func/)
* Kelas [IEnumerable](../)
* Ruang nama [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)