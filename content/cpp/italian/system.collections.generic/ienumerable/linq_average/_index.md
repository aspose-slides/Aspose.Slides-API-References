---
title: LINQ_Average()
second_title: Riferimento API di Aspose.Slides per C++
description: Calcola la media di una sequenza di valori numerici.
type: docs
weight: 365
url: /it/system.collections.generic/ienumerable/linq_average/
---
## IEnumerable::LINQ_Average() metodo

Calcola la media di una sequenza di valori numerici.

```cpp
Source System::Collections::Generic::IEnumerable<Source>::LINQ_Average()
```

### Valore restituito

La media dei valori nella sequenza.

## IEnumerable::LINQ_Average(const Func\<T, ResultType\>\&) metodo

Calcola la media di una sequenza di valori ottenuti invocando una funzione di trasformazione su ciascun elemento della sequenza di input.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<T, ResultType> &selector)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito da selector. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una funzione di trasformazione da applicare a ciascun elemento. |

### Valore restituito

La media dei valori proiettati.

## IEnumerable::LINQ_Average(const Func\<Source, ResultType\>\&) metodo

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Average(const Func<Source, ResultType> &selector)
```

## Vedi anche

* Classe [IEnumerable](../)
* Classe [Func](../../../system/func/)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)