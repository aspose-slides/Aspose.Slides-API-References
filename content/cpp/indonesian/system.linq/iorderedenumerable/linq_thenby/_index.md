---
title: LINQ_ThenBy()
second_title: Referensi API Aspose.Slides untuk C++
description: Melakukan pengurutan lanjutan elemen dalam urutan secara naik menurut sebuah kunci.
type: docs
weight: 27
url: /id/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) method


Melakukan pengurutan lanjutan elemen dalam urutan secara naik berdasarkan sebuah kunci.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Parameter templat

| Parameter | Deskripsi |
| --- | --- |
| Key | Tipe kunci yang dikembalikan oleh keySelector. |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Fungsi untuk mengekstrak kunci dari setiap elemen. |

### Nilai Kembalian

[System::Linq::IOrderedEnumerable](../) yang elemennya diurutkan berdasarkan sebuah kunci.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) method




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IOrderedEnumerable](../)
* Class [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Library [Aspose.Slides](../../../)