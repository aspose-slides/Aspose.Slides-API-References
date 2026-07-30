---
title: LINQ_OrderBy()
second_title: Riferimento API di Aspose.Slides per C++
description: Ordina gli elementi di una sequenza in ordine crescente in base ai valori chiave selezionati da keySelector.
type: docs
weight: 209
url: /it/system.collections.generic/ienumerable/linq_orderby/
---
## IEnumerable::LINQ_OrderBy(const Func\<T, Key\>\&) metodo

Ordina gli elementi di una sequenza in ordine crescente secondo i valori chiave selezionati da keySelector.

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<T>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<T, Key> &keySelector)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| keySelector | Una funzione per estrarre una chiave da un elemento. |

### Valore di ritorno

Un IOrderedEnumerable i cui elementi sono ordinati secondo una chiave

## IEnumerable::LINQ_OrderBy(const Func\<Source, Key\>\&) metodo

```cpp
template<typename Key> SharedPtr<Linq::IOrderedEnumerable<Source>> System::Collections::Generic::IEnumerable<T>::LINQ_OrderBy(const Func<Source, Key> &keySelector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../../../system.linq/iorderedenumerable/)
* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)