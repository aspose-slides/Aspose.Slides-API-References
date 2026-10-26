---
title: BeginGetRequestStream()
second_title: Riferimento API Aspose.Slides per C++
description: Avvia un'operazione asincrona per ottenere un flusso per scrivere dati nella risorsa.
type: docs
weight: 469
url: /it/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione asincrona per ottenere un flusso per scrivere dati nella risorsa.

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare in modo univoco ogni operazione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [HttpWebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)