---
title: UdpClient()
second_title: Référence de l'API Aspose.Slides pour C++
description: Initialise une nouvelle instance de la classe UdpClient.
type: docs
weight: 27
url: /fr/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() constructeur


Initialise une nouvelle instance de la classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) constructeur


Initialise une nouvelle instance de la classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | valeur qui spécifie le schéma d'adressage du socket. |

## UdpClient::UdpClient(int32_t) constructeur


Initialise une nouvelle instance de la classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| port | **int32_t** | le numéro de port local depuis lequel vous prévoyez de communiquer. |

## UdpClient::UdpClient(int32_t, AddressFamily) constructeur


Initialise une nouvelle instance de la classe [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| port | **int32_t** | le numéro de port local depuis lequel vous prévoyez de communiquer. |
| family | [AddressFamily](../../addressfamily/) | valeur qui spécifie le schéma d'adressage du socket. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) constructeur


Initialise une nouvelle instance de la classe [UdpClient](../). param local EP le point de terminaison local auquel vous liez la connexion UDP.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) constructeur


Crée une nouvelle instance de la classe [UdpClient](../) et se connecte à l’hôte distant spécifié sur le port spécifié.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```


### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Le nom de l’hôte DNS distant auquel vous souhaitez vous connecter. |
| port | **int32_t** | le numéro de port local depuis lequel vous prévoyez de communiquer. |

## Voir aussi

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)