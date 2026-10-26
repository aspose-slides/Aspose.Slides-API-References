---
title: Connect()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: Nawiązuje połączenie z określonym zdalnym hostem.
type: docs
weight: 248
url: /pl/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) metoda


Nawiązuje połączenie z określonym zdalnym hostem.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | Nazwa zdalnego hosta do połączenia. |
| port | **int32_t** | Port zdalnego hosta do połączenia. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) metoda


Nawiązuje połączenie z określonym zdalnym hostem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | Adres IP zdalnego hosta. |
| port | **int32_t** | Port zdalnego hosta do połączenia. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) metoda


Nawiązuje połączenie z określonym zdalnym hostem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | Zdalny host do połączenia. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) metoda


Nawiązuje połączenie z określonym zdalnym hostem.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```


### Argumenty

| Parameter | Type | Description |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | Adresy IP zdalnego hosta. |
| port | **int32_t** | Port zdalnego hosta do połączenia. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)