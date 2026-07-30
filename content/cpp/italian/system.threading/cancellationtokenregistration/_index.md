---
title: CancellationTokenRegistration
second_title: Riferimento API Aspose.Slides per C++
description: Rappresenta una registrazione per una callback di token di cancellazione.
type: docs
weight: 27
url: /it/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration classe

Rappresenta una registrazione per una callback di token di cancellazione.

```cpp
class CancellationTokenRegistration
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [Dispose](./dispose/)() | Rilascia la registrazione e rimuove la callback dal [CancellationTokenSource](../cancellationtokensource/) associato. Dopo aver chiamato questo metodo, la callback registrata non verrà più invocata quando il [CancellationTokenSource](../cancellationtokensource/) associato viene annullato. |
## Note

Questa classe consente la deregistrazione di una callback da un token di cancellazione. Quando viene rilasciata, rimuove la callback dal [CancellationTokenSource](../cancellationtokensource/) associato. Questa classe non dovrebbe essere creata direttamente - viene restituita dai metodi di registrazione [CancellationToken](../cancellationtoken/).

## Vedi anche

* Spazio dei nomi [System::Threading](../)
* Libreria [Aspose.Slides](../../)