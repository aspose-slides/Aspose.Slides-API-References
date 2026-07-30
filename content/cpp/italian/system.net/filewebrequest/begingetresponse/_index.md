---
title: BeginGetResponse()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia una richiesta asincrona per la risorsa.
type: docs
weight: 170
url: /it/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia una richiesta asincrona per la risorsa.

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente utilizzati per identificare univocamente ciascuna operazione asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [FileWebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)