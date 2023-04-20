---
title: TcpClient()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 235
url: /cpp/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | The endpoint to which the socket is bound. |

## TcpClient::TcpClient() constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | An address family. |

## TcpClient::TcpClient(String, int32_t) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | A remote host name to connect. |
| port | **int32_t** | A port of the remote host to connect. |

## See Also

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)