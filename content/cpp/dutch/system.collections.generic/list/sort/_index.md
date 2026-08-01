---
title: Sort()
second_title: Aspose.Slides voor C++ API-referentie
description: Sorteert elementen in de lijst.
type: docs
weight: 521
url: /nl/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) methode

Sorteert elementen in de lijst.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Comparator om te gebruiken. |

## List::Sort() methode

Sorteert elementen in de lijst met behulp van de standaardcomparator.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) methode

Sorteert elementen in het lijstdeel.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Beginindex van het deel. |
| count | int | Grootte van het deel. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Comparator om te gebruiken. |

## List::Sort(Comparison\<T\>, bool) methode

Sorteert elementen in de lijst.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) om te gebruiken. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComparer](../../icomparer/)
* Klasse [List](../)
* Klasse [Comparison](../../../system/comparison/)
* Namespace [System::Collections::Generic](../../)
* Bibliotheek [Aspose.Slides](../../../)