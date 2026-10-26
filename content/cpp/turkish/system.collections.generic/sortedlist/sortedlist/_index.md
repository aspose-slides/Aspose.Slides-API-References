---
title: SortedList()
second_title: Aspose.Slides for C++ API Referansı
description: Boş bir liste oluşturur.
type: docs
weight: 1
url: /tr/system.collections.generic/sortedlist/sortedlist/
---
## SortedList::SortedList() yapıcı

Boş bir liste oluşturur.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList()
```

## SortedList::SortedList(const SharedPtr\<IComparer\<TKey\>\>\&) yapıcı

Boş bir liste oluşturur.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IComparer<TKey>> &comparer)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<TKey\>\>\& | [Comparer](../../comparer/) kullanmak için. |

## SortedList::SortedList(const SharedPtr\<IDictionary\<TKey, TValue\>\>\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const SharedPtr<IDictionary<TKey, TValue>> &src)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src | const [SharedPtr](../../../system/sharedptr/)\<[IDictionary](../../idictionary/)\<TKey, TValue\>\>\& | [Dictionary](../../dictionary/) verileri kopyalamak için. |

## SortedList::SortedList(const map_t\&) yapıcı

Kopya yapıcı.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(const map_t &map)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| map | const [map_t](../map_t/)\& | Haritadan veri kopyalamak için. |

## SortedList::SortedList(int) yapıcı

Boş bir liste oluşturur.

```cpp
System::Collections::Generic::SortedList<TKey, TValue>::SortedList(int capacity)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| capacity | int | Ayrılacak eleman sayısı. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [map_t](../map_t/)
* Sınıf [SortedList](../)
* Sınıf [IComparer](../../icomparer/)
* Sınıf [IDictionary](../../idictionary/)
* İsim Uzayı [System::Collections::Generic](../../)
* Kütüphane [Aspose.Slides](../../../)