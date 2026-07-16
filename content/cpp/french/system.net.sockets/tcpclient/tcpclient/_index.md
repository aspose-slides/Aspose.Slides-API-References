---
title: TcpClient()
second_title: Référence de l'API Aspose.Slides pour C++
description: Construit une nouvelle instance.
type: docs
weight: 235
url: /fr/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Le point de terminaison auquel le socket est lié. |

## TcpClient::TcpClient() constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | Une famille d'adresses. |

## TcpClient::TcpClient(String, int32_t) constructeur

Construit une nouvelle instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Un nom d'hôte distant à connecter. |
| port | **int32_t** | Un port de l'hôte distant à connecter. |

## Voir aussi

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPEndPoint](../../../system.net/ipendpoint/)
* Classe [TcpClient](../)
* Classe [String](../../../system/string/)
* Espace de noms [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)