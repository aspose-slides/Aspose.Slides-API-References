---
title: Connect()
second_title: Riferimento API di Aspose.Slides per C++
description: Stabilisce una connessione all'host remoto specificato.
type: docs
weight: 248
url: /it/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metodo

Stabilisce una connessione all'host remoto specificato.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nome host remoto a cui connettersi. |
| port | **int32_t** | Una porta dell'host remoto a cui connettersi. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metodo

Stabilisce una connessione all'host remoto specificato.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'indirizzo IP di un host remoto. |
| port | **int32_t** | Una porta dell'host remoto a cui connettersi. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metodo

Stabilisce una connessione all'host remoto specificato.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Un host remoto a cui connettersi. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metodo

Stabilisce una connessione all'host remoto specificato.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Gli indirizzi IP di un host remoto. |
| port | **int32_t** | Una porta dell'host remoto a cui connettersi. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [TcpClient](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Spazio dei nomi [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)