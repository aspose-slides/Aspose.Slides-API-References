---
title: Yield()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un'attività awaitable che restituisce in modo asincrono il controllo al contesto corrente quando viene attesa.
type: docs
weight: 222
url: /it/system.threading.tasks/yield/
---
## System::Threading::Tasks::Yield() funzione

Crea un'attività awaitable che restituisce in modo asincrono il controllo al contesto corrente quando viene attesa.

```cpp
Runtime::CompilerServices::YieldAwaitable System::Threading::Tasks::Yield()
```

### Valore restituito

Un YieldAwaitable che può essere atteso per restituire il controllo.

## Osservazioni

Questo metodo è utile per forzare un metodo asincrono a restituire il controllo, consentendo l'elaborazione di altri lavori in sospeso prima di continuare.

## Vedi anche

* Classe [YieldAwaitable](../../system.runtime.compilerservices/yieldawaitable/)
* Spazio dei nomi [System::Threading::Tasks](../)
* Libreria [Aspose.Slides](../../)