---
title: TcpClient()
second_title: Riferimento API di Aspose.Slides per C++
description: Costruisce una nuova istanza.
type: docs
weight: 235
url: /it/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Il punto finale a cui è associato il socket. |

## TcpClient::TcpClient() costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Una famiglia di indirizzi. |

## TcpClient::TcpClient(String, int32_t) costruttore

Crea una nuova istanza.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nome host remoto a cui connettersi. |
| port | **int32_t** | Una porta dell'host remoto a cui connettersi. |

## Vedi anche

* Enumerazione [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpClient](../)
* Classe [String](../../../system/string/)
* Spazio dei nomi [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)