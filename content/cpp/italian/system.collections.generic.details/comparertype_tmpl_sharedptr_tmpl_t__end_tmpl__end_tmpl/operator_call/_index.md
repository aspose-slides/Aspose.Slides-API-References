---
title: operator()()
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta i tipi di puntatore che implementano l'interfaccia IComparable.
type: docs
weight: 1
url: /it/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/operator_call/
---
## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Confronta i tipi di puntatore che implementano l’interfaccia [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value, bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valore LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valore RHS. |

### Valore di ritorno

True se **a** è considerato minore di **b**, false altrimenti.

## ComparerType< SharedPtr< T > >::operator()(const System::SharedPtr\<Q\>\&, const System::SharedPtr\<Q\>\&) const method

Confronta i tipi di puntatore che non implementano l’interfaccia [IComparable](../../../system/icomparable/).

```cpp
template<typename Q> std::enable_if<!(std::is_base_of<System::IComparable<System::SharedPtr<Q>>, Q>::value||has_method_compareto_shared_ptr<Q>::value), bool>::type System::Collections::Generic::Details::ComparerType<SharedPtr<T>>::operator()(const System::SharedPtr<Q> &a, const System::SharedPtr<Q> &b) const
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| Q | Tipo da confrontare. |

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valore LHS. |
| b | const [System::SharedPtr](../../../system/sharedptr/)\<Q\>\& | Valore RHS. |

### Valore di ritorno

True se **a** è considerato minore di **b**, false altrimenti.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IComparable](../../../system/icomparable/)
* Struct [has_method_compareto_shared_ptr](../../has_method_compareto_shared_ptr/)
* Struct [ComparerType< SharedPtr< T > >](../)
* Spazio dei nomi [System::Collections::Generic::Details](../../)
* Library [Aspose.Slides](../../../)