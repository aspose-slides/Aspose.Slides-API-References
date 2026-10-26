---
title: EndRead()
second_title: Riferimento API di Aspose.Slides per C++
description: Attende fino al completamento dell'operazione di lettura asincrona specificata.
type: docs
weight: 430
url: /it/system.net.security/sslstream/endread/
---
## SslStream::EndRead(System::SharedPtr\<IAsyncResult\>) metodo

Attende fino al completamento dell'operazione di lettura asincrona specificata.

```cpp
int32_t System::Net::Security::SslStream::EndRead(System::SharedPtr<IAsyncResult> asyncResult) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di lettura asincrona |

### Valore restituito

Il numero di byte letti durante l'operazione di lettura rappresentata da **asyncResult**

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [SslStream](../)
* Namespace [System::Net::Security](../../)
* Libreria [Aspose.Slides](../../../)