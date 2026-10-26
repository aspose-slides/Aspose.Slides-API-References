---
title: invoke()
second_title: Riferimento API Aspose.Slides per C++
description: Invoca tutti i delegati attualmente presenti nella raccolta di delegati. I delegati vengono invocati nello stesso ordine in cui sono stati aggiunti alla raccolta. Il metodo si blocca mentre i delegati vengono eseguiti.
type: docs
weight: 222
url: /it/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/invoke/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes...) const metodo

Invoca tutti i delegati attualmente presenti nella raccolta di delegati. I delegati vengono invocati nello stesso ordine in cui sono stati aggiunti alla raccolta. Il metodo si blocca mentre i delegati vengono eseguiti.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::invoke(ArgumentTypes... args) const
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| args | ArgumentTypes... | Argomenti da passare ai delegati da invocare |

### Valore di ritorno

Valore restituito dall'ultimo delegato invocato

## Vedi anche

* Classe [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)