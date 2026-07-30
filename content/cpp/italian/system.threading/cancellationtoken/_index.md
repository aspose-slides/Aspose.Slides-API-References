---
title: CancellationToken
second_title: Riferimento API Aspose.Slides per C++
description: Propaga la notifica che le operazioni devono essere annullate. Questa classe fornisce un meccanismo per la cancellazione cooperativa tra thread, consentendo a un thread di notificare agli altri che un'operazione deve essere annullata.
type: docs
weight: 14
url: /it/system.threading/cancellationtoken/
---
## CancellationToken classe

Propaga una notifica che le operazioni devono essere annullate. Questa classe fornisce un meccanismo per la cancellazione cooperativa tra thread, consentendo a un thread di notificare agli altri che un'operazione deve essere annullata.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
|  [CancellationToken](./cancellationtoken/)() | Costruttore predefinito. |
| **bool** [get_CanBeCanceled](./get_canbecanceled/)() const | Restituisce se questo token è in grado di trovarsi nello stato annullato. |
| **bool** [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Restituisce se è stata richiesta la cancellazione per questo token. |
| static [CancellationToken](./) [get_None](./get_none/)() | Restituisce un valore [System::Threading::CancellationToken](./) vuoto. |
| [CancellationTokenRegistration](../cancellationtokenregistration/) [Register](./register/)(const [Action](../../system/action/)<>\&) const | Registra una callback che verrà invocata quando viene richiesta la cancellazione. |
| void [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Lancia una OperationCanceledException se è stata richiesta la cancellazione. |
## Osservazioni

Un [CancellationToken](./) può essere annullato solo tramite il suo [CancellationTokenSource](../cancellationtokensource/) associato.

## Vedi anche

* Spazio dei nomi [System::Threading](../)
* Libreria [Aspose.Slides](../../)