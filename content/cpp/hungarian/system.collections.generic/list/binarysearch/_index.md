---
title: BinarySearch()
second_title: Aspose.Slides C++ API referencia
description: Keres egy elemet egy rendezett listában.
type: docs
weight: 339
url: /hu/system.collections.generic/list/binarysearch/
---
## List::BinarySearch(const T\&) const metódus


Keres egy elemet egy rendezett listában.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | A keresett elem. |

### Visszatérési érték

[Index](../../../system/index/) a rendezett listában lévő elem helye vagy a legközelebbi index komplementere.

## List::BinarySearch(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metódus


Keres egy elemet egy rendezett listában.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| item | const T\& | A keresett elem. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) használatához. |

### Visszatérési érték

[Index](../../../system/index/) a rendezett listában lévő elem helye vagy a legközelebbi index komplementere.

## List::BinarySearch(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const metódus


Keres egy elemet egy rendezett listában.

```cpp
int System::Collections::Generic::List<T>::BinarySearch(int index, int count, const T &item, const SharedPtr<System::Collections::Generic::IComparer<T>> &comparer) const
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | [Range](../../../system/range/) kezdet. |
| count | int | [Range](../../../system/range/) méret. |
| item | const T\& | A keresett elem. |
| comparer | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | [Comparer](../../comparer/) használatához. |

### Visszatérési érték

[Index](../../../system/index/) a rendezett listában lévő elem helye vagy a legközelebbi index komplementere.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [List](../)
* Osztály [IComparer](../../icomparer/)
* Névtér [System::Collections::Generic](../../)
* Könyvtár [Aspose.Slides](../../../)