---
title: Sort()
second_title: Aspose.Slides dla C++ - Referencja API
description: Sortuje elementy na liście.
type: docs
weight: 521
url: /pl/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metoda

Sortuje elementy na liście.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Komparator do użycia. |

## List::Sort() metoda

Sortuje elementy na liście przy użyciu domyślnego komparatora.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metoda

Sortuje elementy w wycinku listy.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks początkowy wycinka. |
| count | int | Rozmiar wycinka. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Komparator do użycia. |

## List::Sort(Comparison\<T\>, bool) metoda

Sortuje elementy na liście.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) do użycia. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IComparer](../../icomparer/)
* Klasa [List](../)
* Klasa [Comparison](../../../system/comparison/)
* Przestrzeń nazw [System::Collections::Generic](../../)
* Biblioteka [Aspose.Slides](../../../)