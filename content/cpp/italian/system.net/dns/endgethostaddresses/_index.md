---
title: EndGetHostAddresses()
second_title: Riferimento API Aspose.Slides per C++
description: Attende fino al completamento dell'operazione asincrona specificata per creare una nuova istanza di IPHostEntry-class.
type: docs
weight: 144
url: /it/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) metodo


Attende fino al completamento dell'operazione asincrona specificata per creare una nuova istanza di IPHostEntry-class.

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione asincrona. |

### Valore di ritorno

Una nuova istanza di IPHostEntry-class.

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPAddress](../../ipaddress/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Dns](../)
* Spazio dei nomi [System::Net](../../)
* Library [Aspose.Slides](../../../)