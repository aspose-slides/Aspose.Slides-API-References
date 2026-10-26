---
title: LINQ_SelectMany()
second_title: Riferimento API di Aspose.Slides per C++
description: Proietta ogni elemento di una sequenza e combina le sequenze risultanti in un'unica sequenza.
type: docs
weight: 300
url: /it/system.collections.generic/ienumerable/linq_selectmany/
---
## IEnumerable::LINQ_SelectMany(const Func\<T, SharedPtr\<IEnumerable\<ResultType\>\>\>\&) method


Proietta ogni elemento di una sequenza e combina le sequenze risultanti in un’unica sequenza.

```cpp
template<typename ResultType> SharedPtr<IEnumerable<ResultType>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<T, SharedPtr<IEnumerable<ResultType>>> &selector)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito dal **selector**. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, [SharedPtr](../../../system/sharedptr/)\<[IEnumerable](../)\<ResultType\>\>\>\& | Una funzione di trasformazione. |

### Valore di ritorno

Un [IEnumerable](../) che contiene il risultato dell’invocazione di una funzione di proiezione uno-a-molti su ciascun elemento della sequenza di input.

## IEnumerable::LINQ_SelectMany(const Func\<Source, SharedPtr\<IEnumerable\<Result\>\>\>\&) method




```cpp
template<typename Result> SharedPtr<IEnumerable<Result>> System::Collections::Generic::IEnumerable<T>::LINQ_SelectMany(const Func<Source, SharedPtr<IEnumerable<Result>>> &selector)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Namespace [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)