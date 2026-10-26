---
title: LINQ_Max()
second_title: Riferimento API di Aspose.Slides per C++
description: Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore massimo risultante.
type: docs
weight: 352
url: /it/system.collections.generic/ienumerable/linq_max/
---
## IEnumerable::LINQ_Max(const Func\<T, ResultType\>\&) metodo


Invoca una funzione di trasformazione su ciascun elemento di una sequenza generica e restituisce il valore massimo risultante.

```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<T, ResultType> &selector)
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| ResultType | Il tipo del valore restituito dal selettore. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| selector | const [Func](../../../system/func/)\<T, ResultType\>\& | Una funzione di trasformazione da applicare a ciascun elemento. |

### Valore di ritorno

Il valore massimo nella sequenza.

## IEnumerable::LINQ_Max(const Func\<Source, ResultType\>\&) metodo




```cpp
template<typename ResultType> ResultType System::Collections::Generic::IEnumerable<T>::LINQ_Max(const Func<Source, ResultType> &selector)
```

## Vedi anche

* Classe [Func](../../../system/func/)
* Classe [IEnumerable](../)
* Spazio dei nomi [System::Collections::Generic](../../)
* Libreria [Aspose.Slides](../../../)