---
title: operator()()
second_title: Riferimento API di Aspose.Slides per C++
description: Invoca tutti i delegati attualmente presenti nella collezione di delegati. I delegati sono invocati nello stesso ordine in cui sono stati aggiunti alla collezione. L'operatore blocca l'esecuzione mentre i delegati vengono eseguiti.
type: docs
weight: 235
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const metodo


Invoca tutti i delegati attualmente presenti nella collezione di delegati. I delegati sono invocati nello stesso ordine in cui sono stati aggiunti alla collezione. L'operatore blocca l'esecuzione mentre i delegati vengono eseguiti.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | ArgumentTypes... | Argomenti da passare ai delegati da invocare |

### Valore di ritorno

Valore di ritorno dell'ultimo delegato invocato

## Vedi anche

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)