---
title: BeginWrite()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia un'operazione di scrittura asincrona.
type: docs
weight: 274
url: /it/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di scrittura asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Un buffer contenente i dati da scrivere. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| size | **int32_t** | Il numero di byte da scrivere. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di scrittura asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di scrittura asincrona iniziata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [Object](../../../system/object/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)