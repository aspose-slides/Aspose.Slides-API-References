---
title: SortedSet()
second_title: Aspose.Slides C++ API Referenciája
description: Üres halmazt hoz létre.
type: docs
weight: 1
url: /hu/system.collections.generic/sortedset/sortedset/
---
## SortedSet::SortedSet() konstruktor


Üres halmazt hoz létre.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet()
```

## SortedSet::SortedSet(int) konstruktor


Üres halmazt hoz létre a megadott kapacitással.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(int capacity)
```

## SortedSet::SortedSet(const SharedPtr\<IComparer\<T\>\>\&) konstruktor


Üres halmazt hoz létre, amely a megadott egyenlőség-összehasonlítót használja.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IComparer<T>> &comparer)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) objektum a(z) [SortedSet](../)-hez társítandó. |

## SortedSet::SortedSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor


Létrehozza a [SortedSet](../)-t felsorolható értékek alapján.

```cpp
System::Collections::Generic::SortedSet<T>::SortedSet(const SharedPtr<IEnumerable<T>> &items)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [SortedSet](../)
* Osztály [IComparer](../../icomparer/)
* Osztály [IEnumerable](../../ienumerable/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)