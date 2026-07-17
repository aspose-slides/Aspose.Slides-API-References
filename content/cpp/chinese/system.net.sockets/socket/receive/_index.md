---
title: Receive()
second_title: Aspose.Slides for C++ API 参考
description: 从套接字接收数据并将其写入指定的字节数组。
type: docs
weight: 664
url: /zh/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| size | **int32_t** | 要接收的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| size | **int32_t** | 要接收的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将写入的字节数组。 |
| size | **int32_t** | 要接收的字节数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将写入的字节数组。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将写入的字节数组。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将写入的字节数组。 |

### 返回值

接收的字节数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当接收操作失败时，错误代码将被写入的输出参数。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当接收操作失败时，错误代码将被写入的输出参数。 |

### 返回值

接收的字节数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的数据将写入的字节数组。 |
| offset | **int32_t** | 指定数组中的字节偏移量。 |
| size | **int32_t** | 要接收的字节数，这些字节将从“offset”索引分配到指定的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当接收操作失败时，错误代码将被写入的输出参数。 |

### 返回值

接收的字节数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的数据将写入的字节数组。 |

### 返回值

接收的字节数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的数据将写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |

### 返回值

接收的字节数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) 方法

从套接字接收数据并将其写入指定的字节数组。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的数据将写入的字节数组。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行为。 |
| errorCode | [SocketError](../../socketerror/)\& | 当接收操作失败时，错误代码将被写入的输出参数。 |

### 返回值

接收的字节数。

## 另请参阅

* 枚举 [SocketFlags](../../socketflags/)
* 枚举 [SocketError](../../socketerror/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [Socket](../)
* 类 [IList](../../../system.collections.generic/ilist/)
* 类 [ArraySegment](../../../system/arraysegment/)
* 命名空间 [System::Net::Sockets](../../)
* 库 [Aspose.Slides](../../../)