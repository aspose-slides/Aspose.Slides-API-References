---
title: LINQ_SelectMany()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat proyeksi setiap elemen dari sebuah urutan dan menggabungkan urutan hasil menjadi satu urutan.
type: docs
weight: 300
url: /id/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method

Membuat proyeksi setiap elemen dari sebuah urutan dan menggabungkan urutan hasil menjadi satu urutan.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```

### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh **selector**. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Fungsi transformasi. |

### Nilai Kembali

Sebuah [IEnumerable](../) yang berisi hasil pemanggilan fungsi proyeksi satu-ke-banyak pada setiap elemen dari urutan masukan.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method

```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IEnumerable](../)
* Kelas [Func](../../../system/func/)
* Ruang nama [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)