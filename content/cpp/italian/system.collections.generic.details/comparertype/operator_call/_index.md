---
title: operator()()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta i tipi valore che implementano l'interfaccia IComparable.
type: docs
weight: 1
url: /it/system.collections.generic.details/comparertype/operator_call/
---
## ComparerType::operator()(const Q&, const Q&) const metodo

Confronta i tipi valore che implementano l'interfaccia [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<Q>, Q>::value||has_method_compareto<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const Q& | Valore LHS. |
| b | const Q& | Valore RHS. |

### Valore di ritorno

True se **a** è considerato minore di **b**, false altrimenti.

## ComparerType::operator()(const Q&, const Q&) const metodo

Confronta i tipi valore primitivi e gli oggetti che non implementano l'interfaccia [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<IComparable<Q>, Q>::value||has_method_compareto<Q>::value)&&!std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const Q& | Valore LHS. |
| b | const Q& | Valore RHS. |

### Valore di ritorno

True se **a** è considerato minore di **b**, false altrimenti.

## ComparerType::operator()(const Q&, const Q&) const metodo

Confronta i tipi a virgola mobile.

```cpp
template<typename Q> std::enable_if<std::is_floating_point<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<T>::operator()(const Q &a, const Q &b) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const Q& | Valore LHS. |
| b | const Q& | Valore RHS. |

### Valore di ritorno

True se **a** è considerato minore di **b**, false altrimenti.

## Vedi anche

* Classe [IComparable](../../../system/icomparable/)
* Struttura [has_method_compareto](../../has_method_compareto/)
* Struttura [ComparerType](../)
* Spazio dei nomi [System::Collections::Generic::Details](../../)
* Libreria [Aspose.Slides](../../../)