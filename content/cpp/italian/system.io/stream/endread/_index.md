---
title: EndRead()
second_title: Riferimento API Aspose.Slides per C++
description: Attende finché l'operazione di lettura asincrona specificata non viene completata.
type: docs
weight: 183
url: /it/system.io/stream/endread/
---
## Stream::EndRead(System::SharedPtr\<System::IAsyncResult\>) metodo


Attende fino a quando l'operazione di lettura asincrona specificata viene completata.

```cpp
virtual int System::IO::Stream::EndRead(System::SharedPtr<System::IAsyncResult> asyncResult)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[System::IAsyncResult](../../../system/iasyncresult/)\> | Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta un'operazione di lettura asincrona |

### Valore di ritorno

Il numero di byte letti durante l'operazione di lettura rappresentata da **asyncResult**

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Stream](../)
* Namespace [System::IO](../../)
* Libreria [Aspose.Slides](../../../)