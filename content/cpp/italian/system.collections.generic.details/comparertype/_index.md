---
title: ComparerType
second_title: Riferimento API di Aspose.Slides per C++
description: Confronta gli elementi usando la semantica 'less'.
type: docs
weight: 144
url: /it/system.collections.generic.details/comparertype/
---
## ComparerType struct

Confronta gli elementi usando la semantica 'less'.

```cpp
template<typename T>class ComparerType
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo degli elementi confrontati. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Confronta i tipi di valore che implementano l'interfaccia [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Confronta i tipi di valore primitivi e gli oggetti che non implementano l'interfaccia [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Confronta i tipi a virgola mobile. |

## Vedi anche

* Namespace [System::Collections::Generic::Details](../)
* Libreria [Aspose.Slides](../../)