---
title: Connect()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en anslutning till den angivna fjärrvärden.
type: docs
weight: 248
url: /sv/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) method

Skapar en anslutning till den angivna fjärrvärden.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Ett fjärrvärdsnamn att ansluta till. |
| port | **int32_t** | En port på fjärrvärden att ansluta till. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method

Skapar en anslutning till den angivna fjärrvärden.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | IP-adressen för en fjärrvärd. |
| port | **int32_t** | En port på fjärrvärden att ansluta till. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) method

Skapar en anslutning till den angivna fjärrvärden.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | En fjärrvärd att ansluta till. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) method

Skapar en anslutning till den angivna fjärrvärden.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```

### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | IP-adresserna för en fjärrvärd. |
| port | **int32_t** | En port på fjärrvärden att ansluta till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [TcpClient](../)
* Klass [IPAddress](../../../system.net/ipaddress/)
* Klass [IPEndPoint](../../../system.net/ipendpoint/)
* Namnrymd [System::Net::Sockets](../../)
* Bibliotek [Aspose.Slides](../../../)