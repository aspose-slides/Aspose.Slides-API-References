---
title: EndGetRequestStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento dell'operazione asincrona specificata per ottenere un flusso.
type: docs
weight: 482
url: /it/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) metodo

Attende finché l'operazione asincrona specificata per ottenere un flusso non è completata.

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione asincrona per ottenere un flusso. |

### Valore di ritorno

Il flusso per scrivere dati nella risorsa.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [HttpWebRequest](../)
* Namespace [System::Net](../../)
* Libreria [Aspose.Slides](../../../)