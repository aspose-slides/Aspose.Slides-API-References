---
title: ReceiveMessageFrom()
second_title: Aspose.Slides C++ API 参考
description: 从指定的终结点接收数据并将其写入指定的字节数组。
type: docs
weight: 677
url: /zh/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) 方法


从指定的终结点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被分配的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配给指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程终结点。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 输出参数，将分配数据包信息。 |

### 返回值

接收的字节数。

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) 方法


从指定的终结点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将被分配的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配给指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程终结点。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 输出参数，将分配数据包信息。 |

### 返回值

接收的字节数。

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) 方法


从指定的终结点接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将被分配的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配给指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程终结点。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 输出参数，将分配数据包信息。 |

### 返回值

接收的字节数。

## 另见

* 枚举 [SocketFlags](../../socketflags/)
* 类型别名 [ArrayPtr](../../../system/arrayptr/)
* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [EndPoint](../../../system.net/endpoint/)
* 类 [IPPacketInformation](../../ippacketinformation/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)