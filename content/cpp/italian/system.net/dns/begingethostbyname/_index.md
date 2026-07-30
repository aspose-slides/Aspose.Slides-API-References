---
title: BeginGetHostByName()
second_title: Riferimento API Aspose.Slides per C++
description: Avvia un'operazione asincrona per creare una nuova istanza della classe IPHostEntry utilizzando il nome host specificato.
type: docs
weight: 53
url: /it/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione asincrona per creare una nuova istanza della classe IPHostEntry utilizzando il nome host specificato.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | Un nome host. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare quando l'operazione è completata. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare in modo univoco ogni operazione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [Dns](../)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)