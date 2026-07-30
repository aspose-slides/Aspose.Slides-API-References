---
title: Find()
second_title: Riferimento API di Aspose.Slides per C++
description: Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato.
type: docs
weight: 651
url: /it/system/array/find/
---
## Array::Find(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodo


Cerca il primo elemento nell'array specificato che soddisfa le condizioni del predicato specificato.

```cpp
static T System::Array<T>::Find(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) per cercare un elemento in |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicato che definisce le condizioni per confrontare gli elementi dell'array |

### Valore restituito

Copia del primo elemento nell'array che soddisfa le condizioni definite dal predicato, altrimenti valore predefinito del tipo T

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)