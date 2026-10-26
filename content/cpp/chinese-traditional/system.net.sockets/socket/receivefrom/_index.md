---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API 參考
description: 從指定的端點接收資料，並寫入指定的位元組陣列。
type: docs
weight: 690
url: /zh-hant/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收資料將被指派的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收資料將被指派的位元組陣列。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派到指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收資料將被指派的位元組陣列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收資料將被指派的位元組陣列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |

### 返回值

接收的位元組數。

## 另請參閱

* 列舉 [SocketFlags](../../socketflags/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [EndPoint](../../../system.net/endpoint/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)