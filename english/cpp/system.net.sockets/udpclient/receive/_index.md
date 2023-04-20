---
title: Receive()
second_title: Aspose.Slides for C++ API Reference
description: Returns a datagram sent by a server.
type: docs
weight: 92
url: /cpp/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) method


Returns a datagram sent by a server.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | An [IPEndPoint](../../../system.net/ipendpoint/) that represents the remote host from which the data was sent. |

### Return Value

A byte array where received data will be assigned.

## See Also

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [UdpClient](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)