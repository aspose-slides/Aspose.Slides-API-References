---
title: Connect()
second_title: Aspose.Slides for C++ API Reference
description: Establishes a connection to the specified port on the specified host.
type: docs
weight: 66
url: /cpp/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) method


Establishes a connection to the specified port on the specified host.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | The name of the remote DNS host to which you intend to connect. |
| port | **int32_t** | The local port number from which you intend to communicate. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) method


Establishes a connection with the host at the specified address on the specified port.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | The [IPAddress](../../../system.net/ipaddress/) of the remote host to which to send data. |
| port | **int32_t** | The local port number from which you intend to communicate. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) method


Establishes a connection to a remote end point.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | the endpoint to which you bind the UDP connection. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Class [IPAddress](../../../system.net/ipaddress/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)