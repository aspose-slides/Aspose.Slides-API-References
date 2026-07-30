---
title: TrueForAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Determina se tutti gli elementi dell'array specificato soddisfano le condizioni definite dal predicato specificato.
type: docs
weight: 677
url: /it/system/array/trueforall/
---
## Array::TrueForAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodo


Determina se tutti gli elementi nell'array specificato soddisfano le condizioni definite dal predicato specificato.

```cpp
static bool System::Array<T>::TrueForAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) elementi con i quali verificare le condizioni |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicato che definisce le condizioni con cui verificare gli elementi dell'array |

### Valore di ritorno

true se tutti gli elementi dell'array arr soddisfano le condizioni definite dal predicato match, altrimenti false

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* classe [Array](../)
* spazio dei nomi [System](../../)
* libreria [Aspose.Slides](../../../)