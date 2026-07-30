---
title: EndGetResponse()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento della richiesta asincrona specificata per la risorsa.
type: docs
weight: 508
url: /it/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) metodo

Attende fino al completamento della richiesta asincrona specificata per la risorsa.

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un [IAsyncResult](../../../system/iasyncresult/) oggetto che rappresenta una richiesta asincrona per la risorsa. |

### Valore di ritorno

La risposta web.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [WebResponse](../../webresponse/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [HttpWebRequest](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)