---
title: BeginSend()
second_title: Riferimento API Aspose.Slides per C++
description: Avvia un'operazione di invio asincrona.
type: docs
weight: 495
url: /it/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di invio asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer da cui leggere i dati. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte nell'array specificato a partire dal parametro 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/) | Il comportamento di invio. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente utilizzati per identificare in modo univoco ogni operazione di invio asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di invio asincrona iniziata.

## Vedi anche

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)