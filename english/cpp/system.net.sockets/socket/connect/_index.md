---
title: Connect()
second_title: Aspose.Slides for C++ API Reference
description: Establishes a connection to the specified remote endpoint.
type: docs
weight: 560
url: /cpp/system.net.sockets/socket/connect/
---
## Socket::Connect(System::SharedPtr\<EndPoint\>) method


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<EndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | The remote endpoint. |

## Socket::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | The remote host IP address. |
| port | **int32_t** | The port number of the remote host. |

## Socket::Connect(String, int32_t) method


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(String host, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | The remote host name. |
| port | **int32_t** | The port number of the remote host. |

## Socket::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) method


Establishes a connection to the specified remote endpoint.

```cpp
void System::Net::Sockets::Socket::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | The IP addresses of the remote host. |
| port | **int32_t** | The port number of the remote host. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)