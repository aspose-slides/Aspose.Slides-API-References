---
title: Sort()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Řadí prvky v seznamu.
type: docs
weight: 521
url: /cs/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metoda

Řadí prvky v seznamu.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Komparátor k použití. |

## List::Sort() metoda

Řadí prvky v seznamu pomocí výchozího komparátoru.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metoda

Řadí prvky v části seznamu.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Počáteční index části. |
| count | int | Velikost části. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Komparátor k použití. |

## List::Sort(Comparison\<T\>, bool) metoda

Řadí prvky v seznamu.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) k použití. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IComparer](../../icomparer/)
* třída [List](../)
* třída [Comparison](../../../system/comparison/)
* jmenný prostor [System::Collections::Generic](../../)
* knihovna [Aspose.Slides](../../../)