---
title: UdpClient()
second_title: Riferimento API di Aspose.Slides per C++
description: Inizializza una nuova istanza della classe UdpClient.
type: docs
weight: 27
url: /it/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() costruttore

Inizializza una nuova istanza della classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) costruttore

Inizializza una nuova istanza della classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | value that specifies the addressing scheme of the socket. |

## UdpClient::UdpClient(int32_t) costruttore

Inizializza una nuova istanza della classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| port | **int32_t** | the local port number from which you intend to communicate. |

## UdpClient::UdpClient(int32_t, AddressFamily) costruttore

Inizializza una nuova istanza della classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| port | **int32_t** | the local port number from which you intend to communicate. |
| family | [AddressFamily](../../addressfamily/) | value that specifies the addressing scheme of the socket. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) costruttore

Inizializza una nuova istanza della classe [UdpClient](../). param local EP l'endpoint locale a cui associare la connessione UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) costruttore

Crea una nuova istanza della classe [UdpClient](../) e si collega all'host remoto specificato sulla porta specificata.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | The name of the remote DNS host to which you intend to connect. |
| port | **int32_t** | The local port number from which you intend to communicate. |

## Vedi anche

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [UdpClient](../)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Libreria [Aspose.Slides](../../../)