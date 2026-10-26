---
title: EndGetResponse()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento della richiesta asincrona specificata per la risorsa.
type: docs
weight: 183
url: /it/system.net/filewebrequest/endgetresponse/
---
## FileWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metodo


Attende fino al completamento della richiesta asincrona specificata per la risorsa.

```cpp
virtual System::SharedPtr<WebResponse> System::Net::FileWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta una richiesta asincrona per la risorsa. |

### Valore di ritorno

La risposta web.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [FileWebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)