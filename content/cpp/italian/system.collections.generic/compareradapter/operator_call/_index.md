---
title: operator()()
second_title: Aspose.Slides per C++ Riferimento API
description: Funzione di confronto per tipi con operatore < disponibile.
type: docs
weight: 27
url: /it/system.collections.generic/compareradapter/operator_call/
---
## ComparerAdapter::operator()(const Q\&, const Q\&) const method

[Comparison](../../../system/comparison/) funzione per tipi con operatore < disponibile.

```cpp
template<typename Q> std::enable_if<detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare; modello per la disponibilità della conversione di tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const Q\& | Primo valore da confrontare. |
| y | const Q\& | Secondo valore da confrontare. |

### Valore di ritorno

Vero se **x** è considerato minore di **y**, falso altrimenti.

## ComparerAdapter::operator()(const Q\&, const Q\&) const method

[Comparison](../../../system/comparison/) funzione per tipi con operatore < non disponibile.

```cpp
template<typename Q> std::enable_if<!detail::has_operator_less<Q>::value, bool>::type System::Collections::Generic::ComparerAdapter<T>::operator()(const Q &x, const Q &y) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare; modello per la disponibilità della conversione di tipo. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | const Q\& | Primo valore da confrontare. |
| y | const Q\& | Secondo valore da confrontare. |

### Valore di ritorno

Vero se il comparatore è impostato e **x** è considerato minore di **y**, falso altrimenti.

## Vedi anche

* Struct [ComparerAdapter](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.Slides](../../../)