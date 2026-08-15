---
title: Send()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的資料傳送至 socket。
type: docs
weight: 638
url: /zh-hant/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| size | **int32_t** | 指定資料中必須傳送的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| size | **int32_t** | 指定資料中必須傳送的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| size | **int32_t** | 指定資料中必須傳送的位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::ArrayPtr\<uint8_t\>) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::ArrayView\<uint8_t\>) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) 方法

將指定的資料傳送至 socket。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 要傳送之資料的位元組陣列集合。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 要傳送之資料的位元組陣列集合。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 要傳送之資料的位元組陣列集合。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當傳送操作失敗時，錯誤代碼會被指派給此輸出參數。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) 方法

將指定的資料傳送至 socket。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當傳送操作失敗時，錯誤代碼會被指派給此輸出參數。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 方法

將指定的資料傳送至 socket。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當傳送操作失敗時，錯誤代碼會被指派給此輸出參數。 |

### 回傳值

已傳送的位元組數。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) 方法

將指定的資料傳送至 socket。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 要傳送的資料。 |
| offset | **int32_t** | 指定陣列的位元組偏移。 |
| size | **int32_t** | 從「offset」參數開始的指定陣列位元組數。 |
| socketFlags | [SocketFlags](../../socketflags/) | 傳送行為。 |
| errorCode | [SocketError](../../socketerror/)\& | 當傳送操作失敗時，錯誤代碼會被指派給此輸出參數。 |

### 回傳值

已傳送的位元組數。

## 另請參閱

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)