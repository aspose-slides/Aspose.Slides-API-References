---
title: EndGetRequestStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento dell'operazione asincrona specificata per ottenere un flusso.
type: docs
weight: 313
url: /it/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metodo

Attende fino al completamento dell'operazione asincrona specificata per ottenere un flusso.

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione asincrona per ottenere un flusso. |

### Valore di ritorno

Il flusso per scrivere dati sulla risorsa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [WebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)