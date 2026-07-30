---
title: BeginGetResponse()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia una richiesta asincrona per la risorsa.
type: docs
weight: 274
url: /it/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia una richiesta asincrona per la risorsa.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente utilizzati per identificare in modo univoco ogni operazione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [WebRequest](../)
* Namespace [System::Net](../../)
* Libreria [Aspose.Slides](../../../)