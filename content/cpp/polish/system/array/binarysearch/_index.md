---
title: BinarySearch()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Wykonuje wyszukiwanie binarne w posortowanej tablicy.
type: docs
weight: 612
url: /pl/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) metoda

Wykonuje wyszukiwanie binarne w posortowanej tablicy.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Posortowana tablica, w której wykonywane jest wyszukiwanie |
| item | const T\& | Element do wyszukania |

### Wartość zwracana

[Index](../../index/) wyszukiwanego elementu, jeśli zostanie znaleziony, w przeciwnym razie ujemna liczba całkowita będąca bitową komplementacją indeksu następnego elementu większego od wyszukiwanego elementu lub, jeśli nie ma większego elementu, bitową komplementacją liczby elementów w tablicy.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metoda

NIE ZAIMPLEMENTOWANO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasa [Array](../)
* Klasa [IComparer](../../../system.collections.generic/icomparer/)
* Przestrzeń nazw [System](../../)
* Library [Aspose.Slides](../../../)