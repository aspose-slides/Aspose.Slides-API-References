---
title: BeginConnect()
second_title: Aspose.Slides per C++ Riferimento API
description: Avvia un'operazione di connessione asincrona.
type: docs
weight: 573
url: /it/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | L'endpoint remoto. |
| callback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di connessione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome host remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di connessione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'indirizzo IP remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di connessione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo


Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Gli indirizzi IP del host remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Una callback che verrà chiamata quando l'operazione è completata. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ogni operazione di connessione asincrona. |

### Valore di ritorno

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Object](../../../system/object/)
* Classe [Socket](../)
* Classe [String](../../../system/string/)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Namespace [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)