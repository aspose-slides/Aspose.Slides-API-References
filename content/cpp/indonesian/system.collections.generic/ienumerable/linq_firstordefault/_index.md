---
title: LINQ_FirstOrDefault()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan elemen pertama dari sebuah urutan, atau nilai default jika urutan tersebut kosong.
type: docs
weight: 66
url: /id/system.collections.generic/ienumerable/linq_firstordefault/
---
## IEnumerable::LINQ_FirstOrDefault() metode


Mengembalikan elemen pertama dari sebuah urutan, atau nilai default jika urutan tersebut kosong.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault()
```


### Nilai Kembalian

Elemen pertama dalam urutan atau nilai yang dibangun secara default jika urutan kosong.

## IEnumerable::LINQ_FirstOrDefault(std::function\<bool(T)>) metode


Mengembalikan elemen pertama dari urutan yang memenuhi kondisi tertentu atau nilai default jika tidak ada elemen seperti itu.

```cpp
T System::Collections::Generic::IEnumerable<T>::LINQ_FirstOrDefault(std::function<bool(T)> predicate)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| predicate | std::function\<**bool**(T)> | Fungsi untuk menguji setiap elemen terhadap suatu kondisi. |

### Nilai Kembalian

default(T) jika sumber kosong atau tidak ada elemen yang lulus uji yang ditentukan oleh predicate; jika tidak, elemen pertama dalam sumber yang lulus uji yang ditentukan oleh predicate.

## Lihat Juga

* Kelas [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)