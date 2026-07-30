---
title: Handle()
second_title: Riferimento API di Aspose.Slides per C++
description: Invoca una funzione handler su ogni eccezione interna e rilancia le eccezioni non gestite.
type: docs
weight: 66
url: /it/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) method

Invoca una funzione handler su ogni eccezione interna e rilancia le eccezioni non gestite.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Una funzione che accetta un Exception e restituisce true se è gestito. |

## Note

Se tutte le eccezioni sono gestite, il metodo restituisce normalmente; altrimenti viene sollevata una nuova AggregateException contenente le eccezioni non gestite. 

## Vedi anche

* Typedef [Exception](../../exception/)
* Classe [Func](../../func/)
* Classe [Details_AggregateException](../)
* Spazio dei nomi [System](../../)
* Libreria [Aspose.Slides](../../../)