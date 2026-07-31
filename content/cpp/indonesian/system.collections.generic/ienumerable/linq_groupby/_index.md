---
title: LINQ_GroupBy()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengelompokkan elemen-elemen dalam sebuah urutan.
type: docs
weight: 287
url: /id/system.collections.generic/ienumerable/linq_groupby/
---
## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>) metode


Mengelompokkan elemen-elemen dalam sebuah urutan.

```cpp
template<typename Key> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, T>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Key | Tipe kunci yang dikembalikan oleh keyPredicate |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Fungsi untuk mengekstrak kunci bagi setiap elemen. |

### Nilai Kembalian

Sebuah [IEnumerable](../) yang berisi urutan objek dan sebuah kunci

## IEnumerable::LINQ_GroupBy(System::Func\<T, Key\>, System::Func\<T, Element\>) metode


Mengelompokkan elemen-elemen dalam sebuah urutan.

```cpp
template<typename Key,typename Element> System::SharedPtr<IEnumerable<System::SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<T, Key> keyPredicate, System::Func<T, Element> elementSelector)
```


### Parameter Template

| Parameter | Deskripsi |
| --- | --- |
| Key | Tipe kunci yang dikembalikan oleh keyPredicate |
| Element | Tipe elemen yang dikembalikan oleh elementSelector |

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| keyPredicate | [System::Func](../../../system/func/)\<T, Key\> | Fungsi untuk mengekstrak kunci bagi setiap elemen. |
| elementSelector | [System::Func](../../../system/func/)\<T, Element\> | Fungsi untuk mengekstrak nilai kunci bagi setiap elemen. |

### Nilai Kembalian

Sebuah [IEnumerable](../) yang berisi urutan objek dan sebuah kunci

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>) metode




```cpp
template<typename Key> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Source>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate)
```

## IEnumerable::LINQ_GroupBy(System::Func\<Source, Key\>, System::Func\<Source, Element\>) metode




```cpp
template<typename Key,typename Element> SharedPtr<IEnumerable<SharedPtr<System::Linq::IGrouping<Key, Element>>>> System::Collections::Generic::IEnumerable<T>::LINQ_GroupBy(System::Func<Source, Key> keyPredicate, System::Func<Source, Element> elementSelector)
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IEnumerable](../)
* Kelas [IGrouping](../../../system.linq/igrouping/)
* Kelas [Func](../../../system/func/)
* Ruang Nama [System::Collections::Generic](../../)
* Pustaka [Aspose.Slides](../../../)