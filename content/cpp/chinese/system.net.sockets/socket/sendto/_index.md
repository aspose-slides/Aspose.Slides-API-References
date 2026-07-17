---
title: SendTo()
second_title: Aspose.Slides C++ API 参考
description: 将指定的数据发送到指定的终结点。
type: docs
weight: 651
url: /zh/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 在指定数组中的偏移量（字节）。 |
| size | **int32_t** | 从 'offset' 参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 在指定数组中的偏移量（字节）。 |
| size | **int32_t** | 从 'offset' 参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| offset | **int32_t** | 在指定数组中的偏移量（字节）。 |
| size | **int32_t** | 从 'offset' 参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| size | **int32_t** | 指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| size | **int32_t** | 指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| size | **int32_t** | 指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) 方法

将指定的数据发送到指定的终结点。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 远程终结点。 |

### 返回值

已发送的字节数。

## 另请参见

* 枚举 [SocketFlags](../../socketflags/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [EndPoint](../../../system.net/endpoint/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)