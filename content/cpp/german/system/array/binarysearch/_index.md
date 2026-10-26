---
title: BinarySearch()
second_title: Aspose.Slides für C++ API-Referenz
description: Führt eine binäre Suche im sortierten Array durch.
type: docs
weight: 612
url: /de/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) Methode


Führt eine binäre Suche im sortierten Array durch.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Sortiertes Array, in dem die Suche durchgeführt wird |
| item | const T\& | Ein zu suchendes Element |

### Rückgabewert

[Index](../../index/) des gesuchten Elements, wenn eines gefunden wird, andernfalls ein negativer Integer, der das bitweise Komplement des Index des nächsten Elements, das größer ist als das gesuchte Element, darstellt, oder, falls kein größeres Element existiert, das bitweise Komplement der Anzahl der Elemente im Array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) Methode


NICHT IMPLEMENTIERT.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```


## Siehe auch

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Array](../)
* Klasse [IComparer](../../../system.collections.generic/icomparer/)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)