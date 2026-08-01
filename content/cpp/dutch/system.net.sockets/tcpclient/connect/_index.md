---
title: Connect()
second_title: Aspose.Slides voor C++ API-referentie
description: Stelt een verbinding met de opgegeven externe host tot stand.
type: docs
weight: 248
url: /nl/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) methode

Stelt een verbinding met de opgegeven externe host tot stand.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Een hostnaam van de externe host om verbinding mee te maken. |
| port | **int32_t** | Een poort van de externe host om verbinding mee te maken. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) methode

Stelt een verbinding met de opgegeven externe host tot stand.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Het IP-adres van een externe host. |
| port | **int32_t** | Een poort van de externe host om verbinding mee te maken. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) methode

Stelt een verbinding met de opgegeven externe host tot stand.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Een externe host om verbinding mee te maken. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) methode

Stelt een verbinding met de opgegeven externe host tot stand.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | De IP-adressen van een externe host. |
| port | **int32_t** | Een poort van de externe host om verbinding mee te maken. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [TcpClient](../)
* Klasse [IPAddress](../../../system.net/ipaddress/)
* Klasse [IPEndPoint](../../../system.net/ipendpoint/)
* Naamruimte [System::Net::Sockets](../../)
* Bibliotheek [Aspose.Slides](../../../)