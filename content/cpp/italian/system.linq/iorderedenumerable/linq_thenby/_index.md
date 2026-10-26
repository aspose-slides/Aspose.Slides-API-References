---
title: LINQ_ThenBy()
second_title: Riferimento API di Aspose.Slides per C++
description: Esegue un ordinamento successivo degli elementi in una sequenza in ordine ascendente in base a una chiave.
type: docs
weight: 27
url: /it/system.linq/iorderedenumerable/linq_thenby/
---
## IOrderedEnumerable::LINQ_ThenBy(const Func\<T, Key\>\&) metodo

Esegue un ordinamento successivo degli elementi in una sequenza in ordine ascendente in base a una chiave.

```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<T>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<T, Key> &keySelector)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Key | Il tipo della chiave restituita da keySelector. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| keySelector | const [Func](../../../system/func/)\<T, Key\>\& | Una funzione per estrarre una chiave da ogni elemento. |

### Valore restituito

[System::Linq::IOrderedEnumerable](../) il cui elementi sono ordinati in base a una chiave.

## IOrderedEnumerable::LINQ_ThenBy(const Func\<Source, Key\>\&) metodo




```cpp
template<typename Key> SharedPtr<IOrderedEnumerable<Source>> System::Linq::IOrderedEnumerable<T>::LINQ_ThenBy(const Func<Source, Key> &keySelector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IOrderedEnumerable](../)
* Classe [Func](../../../system/func/)
* Namespace [System::Linq](../../)
* Libreria [Aspose.Slides](../../../)