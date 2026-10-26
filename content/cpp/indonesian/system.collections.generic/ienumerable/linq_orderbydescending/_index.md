---
title: LINQ_OrderByDescending()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengurutkan elemen-elemen dari sebuah urutan dalam urutan menurun berdasarkan nilai kunci yang dipilih oleh keySelector.
type: docs
weight: 222
url: /id/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metode


Mengurutkan elemen-elemen dari sebuah urutan dalam urutan menurun berdasarkan nilai kunci yang dipilih oleh keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| keySelector | Sebuah fungsi untuk mengekstrak kunci dari sebuah elemen. |

### Nilai Kembalian

Sebuah IOrderedEnumerable yang elemennya diurutkan ke urutan menurun berdasarkan kunci

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metode




```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Kelas [Func](../../../system/func/)
* Kelas [IEnumerable](../)
* Ruang Nama [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)