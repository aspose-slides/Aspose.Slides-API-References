---
title: Connect()
second_title: Aspose.Slides for C++ API Reference
description: Establishes a connection to the specified remote host.
type: docs
weight: 248
url: /cpp/system.net.sockets/tcpclient/connect/
---
## TcpClient::Connect(String, int32_t) method


Establishes a connection to the specified remote host.

```cpp
void System::Net::Sockets::TcpClient::Connect(String hostname, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | A remote host name to connect. |
| port | **int32_t** | A port of the remote host to connect. |

## TcpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Establishes a connection to the specified remote host.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPAddress> address, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | The IP address of a remote host. |
| port | **int32_t** | A port of the remote host to connect. |

## TcpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Establishes a connection to the specified remote host.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::SharedPtr<IPEndPoint> remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | A remote host to connect. |

## TcpClient::Connect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t) method


Establishes a connection to the specified remote host.

```cpp
void System::Net::Sockets::TcpClient::Connect(System::ArrayPtr<System::SharedPtr<IPAddress>> ipAddresses, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ipAddresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | The IP addresses of a remote host. |
| port | **int32_t** | A port of the remote host to connect. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [TcpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)