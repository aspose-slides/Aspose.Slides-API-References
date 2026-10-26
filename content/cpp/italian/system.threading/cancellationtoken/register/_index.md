---
title: Register()
second_title: Riferimento API Aspose.Slides per C++
description: Registra una callback che verrà invocata quando viene richiesta la cancellazione.
type: docs
weight: 40
url: /it/system.threading/cancellationtoken/register/
---
## CancellationToken::Register(const Action<>\&) const metodo


Registra una callback che verrà invocata quando viene richiesta la cancellazione.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


### Parametri

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | const [Action](../../../system/action/)<>\& | L'Action<> da eseguire quando viene richiesta la cancellazione. |

### Valore di ritorno

Un oggetto [CancellationTokenRegistration](../../cancellationtokenregistration/) che può essere usato per deregistrare la callback.
## Osservazioni



Se la cancellazione è già stata richiesta, la callback verrà invocata immediatamente. 

La callback dovrebbe essere di breve durata e non bloccante poiché verrà eseguita sul thread che chiama Cancel() sul [CancellationTokenSource](../../cancellationtokensource/). 

## Vedi anche

* Typedef [Action](../../../system/action/)
* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)