---
title: HasOperatorEqualsHelper()
second_title: Riferimento API di Aspose.Slides per C++
description: Funzione di supporto per determinare se una classe specifica ha l'operatore ==.
type: docs
weight: 235
url: /it/system.collections.generic.details/hasoperatorequalshelper/
---
## System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *) function

Funzione di supporto per determinare se una classe specifica ha l'operatore ==.

```cpp
template<class T,typename Dummy> std::true_type System::Collections::Generic::Details::HasOperatorEqualsHelper(T *, T *)
```

### Parametri del modello

| Parametro | Descrizione |
| --- | --- |
| T | Tipo da verificare. |
| Dummy | Argomento fittizio per la magia SFINAE. |

### Valore di ritorno

Valore di std::true_type se l'operatore == è presente e false altrimenti.

## System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *) function

Funzione di supporto per determinare se una classe specifica ha l'operatore ==.

```cpp
std::false_type System::Collections::Generic::Details::HasOperatorEqualsHelper(void *, void *)
```

### Valore di ritorno

Valore di std::true_type se l'operatore == è presente e false altrimenti.

## Vedi anche

* Spazio dei nomi [System::Collections::Generic::Details](../)
* Libreria [Aspose.Slides](../../)