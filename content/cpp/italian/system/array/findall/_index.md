---
title: FindAll()
second_title: Riferimento API di Aspose.Slides per C++
description: Recupera tutti gli elementi che corrispondono alle condizioni definite dal predicato specificato.
type: docs
weight: 664
url: /it/system/array/findall/
---
## Array::FindAll(System::ArrayPtr\<T\>, System::Predicate\<T\>) metodo

Recupera tutti gli elementi che corrispondono alle condizioni definite dal predicato specificato.

```cpp
static System::ArrayPtr<T> System::Array<T>::FindAll(System::ArrayPtr<T> arr, System::Predicate<T> match)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arr | [System::ArrayPtr](../../arrayptr/)\<T\> | [Array](../) per cercare gli elementi in |
| match | [System::Predicate](../../predicate/)\<T\> | Un predicato che definisce le condizioni per confrontare gli elementi dell'array |

### Valore di ritorno

Un [Array](../) contenente tutti gli elementi che corrispondono alle condizioni definite dal predicato specificato, se trovato; altrimenti, un [Array](../) vuoto.

## Vedi anche

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [Predicate](../../predicate/)
* Classe [Array](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)