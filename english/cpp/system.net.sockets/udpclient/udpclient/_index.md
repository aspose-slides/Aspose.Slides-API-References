---
title: UdpClient()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the UdpClient class.
type: docs
weight: 27
url: /cpp/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() constructor


Initializes a new instance of the [UdpClient](../) class.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## See Also

* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## UdpClient::UdpClient([AddressFamily](../../addressfamily/)) constructor


Initializes a new instance of the [UdpClient](../) class.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | value that specifies the addressing scheme of the socket. |

## See Also

* Enum [AddressFamily](../../addressfamily/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## UdpClient::UdpClient(**int32_t**) constructor


Initializes a new instance of the [UdpClient](../) class.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | the local port number from which you intend to communicate. |

## See Also

* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## UdpClient::UdpClient(**int32_t**, [AddressFamily](../../addressfamily/)) constructor


Initializes a new instance of the [UdpClient](../) class.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | the local port number from which you intend to communicate. |
| family | [AddressFamily](../../addressfamily/) | value that specifies the addressing scheme of the socket. |

## See Also

* Enum [AddressFamily](../../addressfamily/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## UdpClient::UdpClient([System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>) constructor


Initializes a new instance of the [UdpClient](../) class. param local EP the local endpoint to which you bind the UDP connection.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
## UdpClient::UdpClient([String](../../../system/string/), **int32_t**) constructor


Creates a new instance of the [UdpClient](../) class and connects to the specified remote host on the specified port.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | The name of the remote DNS host to which you intend to connect. |
| port | **int32_t** | The local port number from which you intend to communicate. |

## See Also

* Class [String](../../../system/string/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)
