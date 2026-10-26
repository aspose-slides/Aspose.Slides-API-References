---
title: Cancel()
second_title: Riferimento API Aspose.Slides per C++
description: Comunica una richiesta di annullamento.
type: docs
weight: 40
url: /it/system.threading/cancellationtokensource/cancel/
---
## CancellationTokenSource::Cancel() metodo


Comunica una richiesta di annullamento.

```cpp
void System::Threading::CancellationTokenSource::Cancel()
```

## Osservazioni



Tutte le callback registrate saranno invocate. 

Le successive chiamate a [get_IsCancellationRequested()](../get_iscancellationrequested/) restituiranno true. 

Le callback vengono eseguite in modo sincrono durante questa chiamata. 

## Vedi anche

* Classe [CancellationTokenSource](../)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)