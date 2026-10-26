---
title: BinarySearch()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Provádí binární vyhledávání ve seřazeném poli.
type: docs
weight: 612
url: /cs/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) metoda

Provádí binární vyhledávání ve seřazeném poli.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Seřazené pole, ve kterém se provádí vyhledávání |
| item | const T\& | Položka, kterou hledáte |

### Návratová hodnota

[Index](../../index/) hledaného prvku, pokud je nalezen, jinak záporné celé číslo, které je bitovým doplněním indexu dalšího prvku většího než hledaný prvek, nebo pokud neexistuje větší prvek, bitovým doplněním počtu prvků v poli.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metoda

NEIMPLEMENTOVÁNO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Viz také

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Třída [Array](../)
* Třída [IComparer](../../../system.collections.generic/icomparer/)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)