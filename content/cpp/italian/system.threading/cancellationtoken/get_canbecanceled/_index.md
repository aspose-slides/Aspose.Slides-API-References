---
title: get_CanBeCanceled()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce se questo token è in grado di trovarsi nello stato annullato.
type: docs
weight: 27
url: /it/system.threading/cancellationtoken/get_canbecanceled/
---
## CancellationToken::get_CanBeCanceled() const metodo

Restituisce se questo token è in grado di trovarsi nello stato annullato.

```cpp
bool System::Threading::CancellationToken::get_CanBeCanceled() const
```

### Valore restituito

true se questo token è in grado di trovarsi nello stato annullato; altrimenti, false.
## Osservazioni

I token creati da [CancellationTokenSource](../../cancellationtokensource/) restituiscono true, mentre il token None restituisce sempre false.

## Vedi anche

* Classe [CancellationToken](../)
* Spazio dei nomi [System::Threading](../../)
* Libreria [Aspose.Slides](../../../)