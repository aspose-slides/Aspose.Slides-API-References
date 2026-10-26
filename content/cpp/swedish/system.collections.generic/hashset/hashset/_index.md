---
title: HashSet()
second_title: Aspose.Slides för C++ API-referens
description: RTTI-information.
type: docs
weight: 1
url: /sv/system.collections.generic/hashset/hashset/
---
## HashSet::HashSet() konstruktor

RTTI-information.

```cpp
System::Collections::Generic::HashSet<T>::HashSet()
```

## Anmärkningar

Skapar en tom uppsättning.

## HashSet::HashSet(int) konstruktor

Skapar en tom uppsättning med angiven kapacitet.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(int capacity)
```

## HashSet::HashSet(const SharedPtr\<IEqualityComparer\<T\>\>\&) konstruktor

Skapar en tom uppsättning som använder den angivna likhetsjämföraren.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEqualityComparer<T>> &comparer)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[IEqualityComparer](../../iequalitycomparer/)\<T\>\>\& | [Comparer](../../comparer/) objekt för att associera med hashset. |

## HashSet::HashSet(const SharedPtr\<IEnumerable\<T\>\>\&) konstruktor

Skapar en hashset baserat på enumererbara värden.

```cpp
System::Collections::Generic::HashSet<T>::HashSet(const SharedPtr<IEnumerable<T>> &items)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [HashSet](../)
* Klass [IEqualityComparer](../../iequalitycomparer/)
* Klass [IEnumerable](../../ienumerable/)
* Namnrymd [System::Collections::Generic](../../)
* Bibliotek [Aspose.Slides](../../../)