---
title: BeginGetHostEntry()
second_title: Riferimento API Aspose.Slides per C++
description: Avvia un'operazione asincrona per creare una nuova istanza della classe IPHostEntry utilizzando la stringa specificata che contiene un nome host o un indirizzo IP.
type: docs
weight: 105
url: /it/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione asincrona per creare una nuova istanza della classe IPHostEntry utilizzando la stringa specificata che contiene un nome host o un indirizzo IP.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | La stringa che contiene un nome host o un indirizzo IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare al completamento dell'operazione. |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare in modo univoco ogni operazione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione asincrona avviata.

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione asincrona per creare una nuova istanza della classe IPHostEntry utilizzando l'indirizzo IP specificato.

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | L'indirizzo IP. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback da chiamare al completamento dell'operazione. |
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
* Classe [IPAddress](../../ipaddress/)
* Spazio dei nomi [System::Net](../../)
* Libreria [Aspose.Slides](../../../)