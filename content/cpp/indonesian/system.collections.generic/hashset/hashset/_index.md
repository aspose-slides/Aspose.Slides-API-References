---
title: HashSet()
second_title: Referensi API Aspose.Slides untuk C++
description: Informasi RTTI.
type: docs
weight: 1
url: /id/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() konstruktor

Informasi RTTI.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Catatan

Membuat set kosong. 

## HashSet::HashSet(int) konstruktor

Membuat set kosong dengan kapasitas yang ditentukan.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr<IEqualityComparer<T>>& ) konstruktor

Membuat set kosong yang menggunakan pembanding kesetaraan yang ditentukan.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)<[IEqualityComparer](../../iequalitycomparer/)<T>>& | [Comparer](../../comparer/) objek untuk diasosiasikan dengan hashset. |

## HashSet::HashSet(const SharedPtr<IEnumerable<T>>& ) konstruktor

Membuat hashset berdasarkan nilai enumerable.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [HashSet](../)
* Kelas [IEqualityComparer](../../iequalitycomparer/)
* Kelas [IEnumerable](../../ienumerable/)
* Ruang Nama [System::Collections::Generic](../../)
* Perpustakaan [Aspose.Slides](../../../)