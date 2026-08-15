---
title: SendTo()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的資料傳送至指定的端點。
type: docs
weight: 651
url: /zh-hant/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 指定陣列中從 'offset' 參數開始的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 指定陣列中從 'offset' 參數開始的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列中以位元組為單位的偏移量。 |
| size | **int32_t** | 指定陣列中從 'offset' 參數開始的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| size | **int32_t** | 指定陣列中的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| size | **int32_t** | 指定陣列中的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| size | **int32_t** | 指定陣列中的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) 方法

將指定資料傳送至指定端點。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 遠端端點。 |

### 返回值

已傳送的位元組數。

## 另見

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)