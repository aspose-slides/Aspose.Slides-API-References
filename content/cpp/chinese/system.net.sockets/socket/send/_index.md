---
title: Send()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的数据发送到套接字。
type: docs
weight: 638
url: /zh/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| size | **int32_t** | 必须发送的指定数据的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| size | **int32_t** | 必须发送的指定数据的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| size | **int32_t** | 必须发送的指定数据的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::ArrayPtr\<uint8_t\>) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) 方法

将指定的数据发送到套接字。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |

### 返回值

已发送的字节数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 必须发送的数据的字节数组集合。 |

### 返回值

已发送的字节数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 必须发送的数据的字节数组集合。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 必须发送的数据的字节数组集合。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当发送操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

已发送的字节数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) 方法

将指定的数据发送到套接字。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |

### 返回值

已发送的字节数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当发送操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

将指定的数据发送到套接字。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当发送操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

已发送的字节数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) 方法

将指定的数据发送到套接字。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要发送的数据。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 从'offset'参数开始的指定数组中的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 发送行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当发送操作失败时，错误代码将被分配到的输出参数。 |

### 返回值

已发送的字节数。

## 另见

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)