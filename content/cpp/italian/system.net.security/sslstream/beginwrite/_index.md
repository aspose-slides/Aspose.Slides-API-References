---
title: BeginWrite()
second_title: Riferimento API di Aspose.Slides per C++
description: Avvia un'operazione di scrittura asincrona.
type: docs
weight: 443
url: /it/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) method

Avvia un'operazione di scrittura asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | L'array di byte su cui scrivere i dati. |
| offset | **int32_t** | L'offset in byte nell'array specificato. |
| count | **int32_t** | Il numero di byte da scrivere. |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback da invocare quando l'operazione è completata. |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di scrittura asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di scrittura asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [Object](../../../system/object/)
* Classe [SslStream](../)
* Spazio dei nomi [System::Net::Security](../../)
* Libreria [Aspose.Slides](../../../)