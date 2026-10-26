---
title: LINQ_OrderBy()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengurutkan elemen-elemen dari sebuah urutan secara naik berdasarkan nilai kunci yang dipilih oleh keySelector.
type: docs
weight: 209
url: /id/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) metode

Mengurutkan elemen-elemen dari sebuah urutan secara naik berdasarkan nilai kunci yang dipilih oleh keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Parameter Templat

| Parameter | Description |
| --- | --- |
| keySelector | Fungsi untuk mengekstrak kunci dari sebuah elemen. |

### Nilai Kembalian

Sebuah IOrderedEnumerable yang elemennya diurutkan berdasarkan sebuah kunci

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) metode

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Kelas [Func](../../../system/func/)
* Kelas [IEnumerable](../)
* Ruang nama [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)