---
title: EndReceive()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento dell'operazione di ricezione asincrona specificata.
type: docs
weight: 534
url: /it/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) method


Attende fino al completamento dell'operazione di ricezione asincrona specificata.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di ricezione asincrona. |

### Valore di ritorno

Il numero di byte ricevuti.

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) method


Attende fino al completamento dell'operazione di ricezione asincrona specificata.

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di ricezione asincrona. |
| errorCode | [SocketError](../../socketerror/)\& | Il parametro di output in cui verrà assegnato il codice di errore quando l'operazione di ricezione fallisce. |

### Valore di ritorno

Il numero di byte ricevuti.

## Vedi anche

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Socket](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)