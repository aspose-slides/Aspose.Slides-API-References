---
title: HashSet()
second_title: Aspose.Slides pro C++ API Reference
description: Informace o RTTI.
type: docs
weight: 1
url: /cs/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() konstruktor

RTTI information.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Poznámky

Vytvoří prázdnou sadu. 
## HashSet::HashSet(int) konstruktor

Vytvoří prázdnou sadu s určenou kapacitou.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) konstruktor

Vytvoří prázdnou sadu, která používá zadaný komparátor rovnosti.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objekt, který má být spojen s hashsetem. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

Vytvoří hashset na základě enumerovatelných hodnot.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HashSet](../)
* Class [IEqualityComparer](../../iequalitycomparer/)
* Class [IEnumerable](../../ienumerable/)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)