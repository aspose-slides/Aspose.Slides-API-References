---
title: ComparerType< SharedPtr< T > >
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta gli elementi usando la semantica 'less'.
type: docs
weight: 157
url: /it/system.collections.generic.details/comparertype_tmpl_sharedptr_tmpl_t__end_tmpl__end_tmpl/
---
## ComparerType< SharedPtr< T > > struct


Confronta gli elementi usando la semantica 'less'.

```cpp
template<typename T>class ComparerType< SharedPtr< T > >
```


### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo degli elementi confrontati. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Confronta i tipi di puntatore che implementano l'interfaccia [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[System::IComparable](../../system/icomparable/)\<[System::SharedPtr](../../system/sharedptr/)\<Q\>\>, Q\>::value||[has_method_compareto_shared_ptr](../has_method_compareto_shared_ptr/)\<Q\>::value), **bool**\>::type [operator()](./operator_call/)(const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&, const [System::SharedPtr](../../system/sharedptr/)\<Q\>\&) const | Confronta i tipi di puntatore che non implementano l'interfaccia [IComparable](../../system/icomparable/). |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic::Details](../)
* Libreria [Aspose.Slides](../../)