---
title: Send()
second_title: Aspose.Slides for C++ API Reference
description: Sends a UDP datagram to the host at the remote end point.
type: docs
weight: 79
url: /system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) method


Sends a UDP datagram to the host at the remote end point.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | An array of type [Byte](../../../system/byte/) to send |
| bytes | **int32_t** | The number of bytes in the datagram. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | An [IPEndPoint](../../../system.net/ipendpoint/) that represents the host and port to which to send the datagram. |

### Return Value

The number of bytes that are sent.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) method


Sends a UDP datagram to the specified port on the specified remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | An array of type [Byte](../../../system/byte/) to send |
| bytes | **int32_t** | The number of bytes in the datagram. |
| hostname | [String](../../../system/string/) | A name of the remote host. |
| port | **int32_t** | A remote port number. |

### Return Value

The number of bytes that are sent.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) method


Sends a UDP datagram to a remote host.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | An array of type [Byte](../../../system/byte/) to send. |
| bytes | **int32_t** | The number of bytes in the datagram. |

### Return Value

The number of bytes that are sent.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)