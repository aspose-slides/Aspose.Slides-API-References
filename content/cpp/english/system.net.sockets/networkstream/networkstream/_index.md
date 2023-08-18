---
title: NetworkStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 170
url: /system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | Specifies the access type given to the instance over the specified socket. |
| ownsSocket | **bool** | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | The socket that is used for sending and receiving data. |
| ownsSocket | **bool** | A value that indicates if the current instance takes ownership of the specified socket when the value is true. |

## See Also

* Enum [FileAccess](../../../system.io/fileaccess/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../../socket/)
* Class [NetworkStream](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)