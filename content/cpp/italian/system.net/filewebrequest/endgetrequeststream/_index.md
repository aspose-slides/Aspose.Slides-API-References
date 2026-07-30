---
title: EndGetRequestStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende finché l'operazione asincrona specificata per ottenere un flusso non termina.
type: docs
weight: 157
url: /it/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) method


Attende finché l'operazione asincrona specificata per ottenere un flusso non termina.

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione asincrona per ottenere un flusso. |

### Valore restituito

Il flusso per scrivere dati nella risorsa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [FileWebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)