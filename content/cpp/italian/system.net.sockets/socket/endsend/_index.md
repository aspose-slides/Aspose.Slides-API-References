---
title: EndSend()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento dell'operazione di invio asincrona specificata.
type: docs
weight: 508
url: /it/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) metodo

Attende fino al completamento dell'operazione di invio asincrona specificata.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di invio asincrona. |

### Valore di ritorno

Il numero di byte inviati.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) metodo

Attende fino al completamento dell'operazione di invio asincrona specificata.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di invio asincrona. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output in cui verrà assegnato il codice di errore quando l'operazione di invio fallisce. |

### Valore di ritorno

Il numero di byte inviati.

## Vedi anche

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)