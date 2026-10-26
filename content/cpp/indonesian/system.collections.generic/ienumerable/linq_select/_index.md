---
title: LINQ_Select()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah elemen dari sebuah urutan.
type: docs
weight: 248
url: /id/system.collections.generic/ienumerable/linq_select/
---
## IEnumerable::LINQ_Select(const Func\<T, ResultType\>\&) metode


Mengubah elemen dari sebuah urutan.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, ResultType> &selector)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh **selector**. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Fungsi transformasi. |

### Nilai Kembali

Sebuah [IEnumerable](../) yang berisi elemen yang dikembalikan oleh fungsi **selector**.

## IEnumerable::LINQ_Select(const Func\<T, int32_t, ResultType\>\&) metode


Mengubah setiap elemen dari sebuah urutan menjadi bentuk baru dengan menyertakan indeks elemen.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<T, int32_t, ResultType> &selector)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| ResultType | Tipe nilai yang dikembalikan oleh **selector**. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, **int32_t**, ResultType\>\& | Fungsi transformasi. |

### Nilai Kembali

Sebuah [IEnumerable](../) yang berisi elemen yang dikembalikan oleh fungsi **selector**.

## IEnumerable::LINQ_Select(const Func\<Source, Result\>\&) metode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, Result> &selector)
```

## IEnumerable::LINQ_Select(const Func\<Source, int32_t, Result\>\&) metode




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_Select(const Func<Source, int32_t, Result> &selector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IEnumerable](../)
* Kelas [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)