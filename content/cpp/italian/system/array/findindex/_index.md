---
title: FindIndex()
second_title: Aspose.Slides per C++ – Riferimento API
description: Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato.
type: docs
weight: 638
url: /it/system/array/findindex/
---
## Array::FindIndex(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodo

Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato.

```cpp
static int System::Array<T>::FindIndex(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) per cercare un elemento in |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicato che definisce le condizioni per confrontare gli elementi dell'array |

### Valore di ritorno

L'indice del primo elemento nell'array che soddisfa le condizioni definite dal predicato, altrimenti -1

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)