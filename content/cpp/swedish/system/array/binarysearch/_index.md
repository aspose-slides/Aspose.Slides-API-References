---
title: BinarySearch()
second_title: Aspose.Slides för C++ API-referens
description: Utför binärsökning i den sorterade arrayen.
type: docs
weight: 612
url: /sv/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) metod

Utför binärsökning i den sorterade arrayen.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Sorterad array att söka i |
| item | const T\& | Ett element att söka efter |

### Returvärde

[Index](../../index/) av det sökta elementet om ett hittas, annars ett negativt heltal som är det bitvisa komplementet av indexet för nästa element som är större än det sökta elementet eller, om det inte finns något större element, det bitvisa komplementet av antalet element i arrayen.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metod

INTE IMPLEMENTERAD.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klass [Array](../)
* Klass [IComparer](../../../system.collections.generic/icomparer/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)