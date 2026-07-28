---
title: Sort()
second_title: Aspose.Slides for C++ API referencia
description: Rendezi a lista elemeit.
type: docs
weight: 521
url: /hu/system.collections.generic/list/sort/
---
## List::Sort(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) metódus

Rendezi a lista elemeit.

```cpp
void System::Collections::Generic::List<T>::Sort(const SharedPtr<System::Collections::Generic::IComparer<T>> &comparator)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| comparator | const [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\>\& | Használandó összehasonlító. |

## List::Sort() metódus

Rendezi a lista elemeit az alapértelmezett összehasonlítóval.

```cpp
void System::Collections::Generic::List<T>::Sort()
```

## List::Sort(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) metódus

Rendezi a lista szelet elemeit.

```cpp
void System::Collections::Generic::List<T>::Sort(int index, int count, SharedPtr<System::Collections::Generic::IComparer<T>> comparator)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| index | int | A szelet kezdő indexe. |
| count | int | A szelet mérete. |
| comparator | [SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../../icomparer/)\<T\>\> | Használandó összehasonlító. |

## List::Sort(Comparison\<T\>, bool) metódus

Rendezi a lista elemeit.

```cpp
void System::Collections::Generic::List<T>::Sort(Comparison<T> comparison, bool)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| comparison | [Comparison](../../../system/comparison/)\<T\> | [Comparison](../../../system/comparison/) a használathoz. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComparer](../../icomparer/)
* Osztály [List](../)
* Osztály [Comparison](../../../system/comparison/)
* Névtér [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)