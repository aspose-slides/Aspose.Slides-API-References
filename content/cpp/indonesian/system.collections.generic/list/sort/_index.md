---
title: Sort()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengurutkan elemen dalam daftar.
type: docs
weight: 521
url: /id/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metode

Mengurutkan elemen dalam daftar.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparator yang akan digunakan. |

## List::Sort() metode

Mengurutkan elemen dalam daftar menggunakan comparator bawaan.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metode

Mengurutkan elemen dalam potongan daftar.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks awal irisan. |
| count | int | Ukuran irisan. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparator yang akan digunakan. |

## List::Sort(Comparison\<T\>, bool) metode

Mengurutkan elemen dalam daftar.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) yang akan digunakan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IComparer](../../icomparer/)
* Kelas [List](../)
* Kelas [Comparison](../../../system/comparison/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)