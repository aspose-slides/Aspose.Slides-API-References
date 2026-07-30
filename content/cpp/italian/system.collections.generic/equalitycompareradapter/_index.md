---
title: EqualityComparerAdapter
second_title: Riferimento API Aspose.Slides per C++
description: "Adattatore che consente l'uso di IEqualityComparer con collezioni e algoritmi in stile STL. Utilizza IEqualityComparer, se impostato. Se non impostato, utilizza l'operatore ==, Object::Equals o T::Equals, a seconda di quale sia disponibile."
type: docs
weight: 664
url: /it/system.collections.generic/equalitycompareradapter/
---
## EqualityComparerAdapter struct

Adattatore che consente l'uso di [IEqualityComparer](../iequalitycomparer/) con collezioni e algoritmi in stile STL. Utilizza [IEqualityComparer](../iequalitycomparer/), se impostato. Se non impostato, utilizza l'operatore ==, [Object::Equals](../../system/object/equals/) o T::Equals, a seconda di quale sia disponibile.

```cpp
template<class T>class EqualityComparerAdapter
```

### Parametri del template

| Parametro | Descrizione |
| --- | --- |
| T | Tipo da confrontare. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [EqualityComparerAdapter](./equalitycompareradapter/)() | Crea un adattatore che non utilizza alcun comparatore. |
|  [EqualityComparerAdapter](./equalitycompareradapter/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Crea un adattatore con il comparatore fornito. |
| **bool** [operator()](./operator_call/)(const T\&, const T\&) const | Confronta due oggetti. |
| void [set_EqualityComparator](./set_equalitycomparator/)(const [SharedPtr](../../system/sharedptr/)\<[IEqualityComparer](../iequalitycomparer/)\<T\>\>\&) | Imposta il comparatore. |

## Vedi anche

* Spazio dei nomi [System::Collections::Generic](../)
* Libreria [Aspose.Slides](../../)