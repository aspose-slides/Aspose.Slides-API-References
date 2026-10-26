---
title: Connect()
second_title: Riferimento API di Aspose.Slides per C++
description: Stabilisce una connessione all'endpoint remoto specificato.
type: docs
weight: 560
url: /it/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) metodo


Stabilisce una connessione all'endpoint remoto specificato.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | L'endpoint remoto. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) metodo


Stabilisce una connessione all'endpoint remoto specificato.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | L'indirizzo IP dell'host remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |

## Socket::Connect(String, int32_t) metodo


Stabilisce una connessione all'endpoint remoto specificato.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| host | [String](../../../system/string/) | Il nome dell'host remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metodo


Stabilisce una connessione all'endpoint remoto specificato.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Gli indirizzi IP dell'host remoto. |
| port | **int32_t** | Il numero di porta dell'host remoto. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [EndPoint](../../../system.net/endpoint/)
* Classe [Socket](../)
* Classe [IPAddress](../../../system.net/ipaddress/)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)