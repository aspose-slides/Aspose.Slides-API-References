---
title: Receive()
second_title: Aspose.Slides for C++ API 參考文件
description: 從 socket 接收資料並寫入指定的位元組陣列。
type: docs
weight: 664
url: /zh-hant/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::ArrayPtr\<uint8_t\>) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將被指派的位元組陣列。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當接收操作失敗時，錯誤代碼將被指派到的輸出參數。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當接收操作失敗時，錯誤代碼將被指派到的輸出參數。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當接收操作失敗時，錯誤代碼將被指派到的輸出參數。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的資料將被指派的位元組陣列。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |

### 返回值

接收到的位元組數。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) method


從 socket 接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 接收的資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當接收操作失敗時，錯誤代碼將被指派到的輸出參數。 |

### 返回值

接收到的位元組數。

## 參見

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)