---
title: LINQ_Min()
second_title: Riferimento API di Aspose.Slides per C++
description: Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore minimo risultante.
type: docs
weight: 339
url: /it/system.collections.generic/ienumerable/linq_min/
---
## IEnumerable::LINQ_Min(const Func\<T, ResultType\>\&) metodo


Invoca una funzione di trasformazione su ogni elemento di una sequenza generica e restituisce il valore minimo risultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<T, ResultType> &selector)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito dal selettore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una funzione di trasformazione da applicare a ogni elemento. |

### Valore restituito

Il valore minimo nella sequenza.

## IEnumerable::LINQ_Min(const Func\<Source, ResultType\>\&) metodo




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Min(const Func<Source, ResultType> &selector)
```

## Vedi anche

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)