---
title: BinarySearch()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue una ricerca binaria nell'array ordinato.
type: docs
weight: 612
url: /it/system/array/binarysearch/
---
## Array::BinarySearch(System::ArrayPtr\<T\>, const T\&) metodo

Esegue una ricerca binaria nell'array ordinato.

```cpp
static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const T &item)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | Array ordinato in cui eseguire la ricerca |
| item | const T\& | Un elemento da cercare |

### Valore di ritorno

[Index](../../index/) dell'elemento cercato se ne viene trovato uno, altrimenti un intero negativo che è il complemento a bit dell'indice del prossimo elemento maggiore dell'elemento cercato oppure, se non esiste un elemento maggiore, il complemento a bit del numero di elementi nell'array.

## Array::BinarySearch(System::ArrayPtr\<T\>, const Y\&, const SharedPtr\<Collections::Generic::IComparer\<Z\>\>\&) metodo

NON IMPLEMENTATO.

```cpp
template<typename Y,typename Z> static int System::Array<T>::BinarySearch(System::ArrayPtr<T> arr, const Y &item, const SharedPtr<Collections::Generic::IComparer<Z>> &comparer)
```

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Array](../)
* Class [IComparer](../../../system.collections.generic/icomparer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)