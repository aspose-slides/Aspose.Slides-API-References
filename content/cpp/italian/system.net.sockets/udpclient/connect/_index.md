---
title: Connect()
second_title: Riferimento API di Aspose.Slides per C++
description: Stabilisce una connessione alla porta specificata sull'host specificato.
type: docs
weight: 66
url: /it/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) metodo


Stabilisce una connessione alla porta specificata sull'host specificato.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Il nome dell'host DNS remoto a cui si intende connettersi. |
| port | **int32_t** | Il numero di porta locale da cui si intende comunicare. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metodo


Stabilisce una connessione con l'host all'indirizzo specificato sulla porta specificata.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Il [IPAddress](../../../system.net/ipaddress/) dell'host remoto a cui inviare i dati. |
| port | **int32_t** | Il numero di porta locale da cui si intende comunicare. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) metodo


Stabilisce una connessione a un punto finale remoto.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | il punto finale a cui associare la connessione UDP. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)