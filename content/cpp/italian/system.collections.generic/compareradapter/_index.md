---
title: ComparerAdapter
second_title: Riferimento API di Aspose.Slides per C++
description: Adattatore per utilizzare IComparer nell'ambiente STL. Usa IComparer se impostato; altrimenti, usa l'operatore < (se disponibile) o restituisce false (se non lo è).
type: docs
weight: 638
url: /it/system.collections.generic/compareradapter/
---
## ComparerAdapter struct

Adattatore per utilizzare [IComparer](../icomparer/) nell'ambiente STL. Usa [IComparer](../icomparer/) se impostato; altrimenti, usa l'operatore < (se disponibile) o restituisce false (se non lo è).

```cpp
template<class T>class ComparerAdapter
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo da confrontare. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [ComparerAdapter](./compareradapter/)() | Costruisce l'adattatore senza alcun comparatore disponibile. |
|  [ComparerAdapter](./compareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Costruisce l'adattatore. |
| std::enable_if\<detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funzione per i tipi con operatore < disponibile. |
| std::enable_if<\!detail::has_operator_less\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | [Comparison](../../system/comparison/) funzione per i tipi con operatore < non disponibile. |
| void [set_Comparator](./set_comparator/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<T\>\>\&) | Imposta l'oggetto comparatore. |

## Vedi anche

* Namespace [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)