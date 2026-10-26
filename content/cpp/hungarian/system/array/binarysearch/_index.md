---
title: BinarySearch()
second_title: Aspose.Slides for C++ API Referenciája
description: Bináris keresést hajt végre a rendezett tömbben.
type: docs
weight: 612
url: /hu/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) metódus

Rendezett tömbben hajt végre bináris keresést.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Rendezett tömb, amelyben a keresést el kell végezni |
| item | const T\& | A keresendő elem |

### Visszatérési érték

[Index](../../index/) a keresett elem, ha megtalálható, egyébként egy negatív egész szám, amely a keresett elemnél nagyobb következő elem indexének bitbeli komplementere, vagy ha nincs nagyobb elem, a tömb elemeinek számának bitbeli komplementere.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metódus

NINCS MEGVALÓSÍTVA.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Lásd még

* Típusdefiníció [ArrayPtr](../../arrayptr/)
* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Array](../)
* Osztály [IComparer](../../../system.collections.generic/icomparer/)
* Névtere [System](../../)
* Könyvtár [Aspose.Slides](../../../)