---
title: BeginGetRequestStream()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia un'operazione asincrona per ottenere un flusso per scrivere dati nella risorsa.
type: docs
weight: 300
url: /it/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione asincrona per ottenere un flusso per scrivere dati nella risorsa.

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente utilizzati per identificare univocamente ogni operazione asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [WebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)