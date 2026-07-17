---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的端点接收数据并将其写入指定的字节数组。
type: docs
weight: 690
url: /zh/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将被写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将被写入的字节数组。 |
| size | **int32_t** | 要接收的字节数，这些字节将从 'offset' 索引处分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将被写入的字节数组。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) 方法

从指定的端点接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将被写入的字节数组。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 远程端点。 |

### 返回值

接收的字节数。

## 另请参见

* 枚举 [SocketFlags](../../socketflags/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [EndPoint](../../../system.net/endpoint/)
* 类 [Socket](../)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)