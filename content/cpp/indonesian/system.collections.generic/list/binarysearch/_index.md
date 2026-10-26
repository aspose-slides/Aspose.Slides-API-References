---
title: BinarySearch()
second_title: Referensi API Aspose.Slides untuk C++
description: Mencari item dalam daftar terurut.
type: docs
weight: 339
url: /id/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const metode


Mencari item dalam daftar yang terurut.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | const T\& | Item yang dicari. |

### Nilai Kembali

[Index](../../../system/index/) dari item dalam daftar terurut atau komplemen indeks terdekat.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metode


Mencari item dalam daftar yang terurut.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| item | const T\& | Item yang dicari. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) untuk digunakan. |

### Nilai Kembali

[Index](../../../system/index/) dari item dalam daftar terurut atau komplemen indeks terdekat.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metode


Mencari item dalam daftar yang terurut.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) awal. |
| count | int | [Range](../../../system/range/) ukuran. |
| item | const T\& | Item yang dicari. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) untuk digunakan. |

### Nilai Kembali

[Index](../../../system/index/) dari item dalam daftar terurut atau komplemen indeks terdekat.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [List](../)
* Kelas [IComparer](../../icomparer/)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)