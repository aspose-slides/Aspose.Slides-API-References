---
title: SortedList()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat daftar kosong.
type: docs
weight: 1
url: /id/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() konstruktor


Membuat daftar kosong.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) konstruktor


Membuat daftar kosong.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) untuk digunakan. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) konstruktor


Konstruktor penyalinan.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) untuk menyalin data dari. |

## SortedList::SortedList(const map_t\&) konstruktor


Konstruktor penyalinan.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Peta untuk menyalin data dari. |

## SortedList::SortedList(int) konstruktor


Membuat daftar kosong.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| capacity | int | Jumlah elemen untuk disisihkan. |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Class [SortedList](../)
* Class [IComparer](../../icomparer/)
* Class [IDictionary](../../idictionary/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)