---
title: LINQ_OrderByDescending()
second_title: Riferimento API di Aspose.Slides per C++
description: Ordina gli elementi di una sequenza in ordine discendente in base ai valori chiave selezionati da keySelector.
type: docs
weight: 222
url: /it/system.collections.generic/ienumerable/linq_orderbydescending/
---
## IEnumerable::LINQ_OrderByDescending(const Func\<T, Key\>\&) metodo

Ordina gli elementi di una sequenza in ordine discendente in base ai valori chiave selezionati da keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<T, Key> &keySelector)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| keySelector | Una funzione per estrarre una chiave da un elemento. |

### Valore di ritorno

Un IOrderedEnumerable i cui elementi sono ordinati in ordine discendente della chiave

## IEnumerable::LINQ_OrderByDescending(const Func\<Source, Key\>\&) metodo


```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderByDescending(const Func<Source, Key> &keySelector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)