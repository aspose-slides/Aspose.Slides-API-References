---
title: BeginConnect()
second_title: Aspose.Slides per C++ API Reference
description: Avvia un'operazione di connessione asincrona.
type: docs
weight: 261
url: /it/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Un nome host remoto. |
| port | **int32_t** | Una porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un callback che verrà chiamato al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ciascuna operazione di connessione asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'indirizzo IP di un host remoto. |
| port | **int32_t** | Una porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un callback che verrà chiamato al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ciascuna operazione di connessione asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) metodo

Avvia un'operazione di connessione asincrona.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Gli indirizzi IP di un host remoto. |
| port | **int32_t** | Una porta dell'host remoto. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | Un callback che verrà chiamato al completamento dell'operazione. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | Dati forniti dall'utente usati per identificare univocamente ciascuna operazione di connessione asincrona. |

### Valore restituito

Un oggetto [IAsyncResult](../../../system/iasyncresult/) che rappresenta l'operazione di connessione asincrona avviata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAsyncResult](../../../system/iasyncresult/)
* Classe [String](../../../system/string/)
* Classe [Object](../../../system/object/)
* Classe [TcpClient](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)