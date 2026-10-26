---
title: HashSet()
second_title: Aspose.Slides for C++ API Referencia
description: RTTI információ.
type: docs
weight: 1
url: /hu/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() konstruktor

RTTI információ.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Megjegyzések

Üres halmazt hoz létre. 

## HashSet::HashSet(int) konstruktor

Üres halmazt hoz létre a megadott kapacitással.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) konstruktor

Üres halmazt hoz létre, amely a megadott egyenlőség-összehasonlítót használja.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objektum, amely a hashsethez társítandó. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

HashSet-et hoz létre a felsorolható értékek alapján.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [HashSet](../)
* Osztály [IEqualityComparer](../../iequalitycomparer/)
* Osztály [IEnumerable](../../ienumerable/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)