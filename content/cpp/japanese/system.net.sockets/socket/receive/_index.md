---
title: Receive()
second_title: Aspose.Slides for C++ API リファレンス
description: ソケットからデータを受信し、指定されたバイト配列に書き込みます。
type: docs
weight: 664
url: /ja/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 受信するバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 受信するバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 受信するバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 受信操作が失敗したときにエラーコードが割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 受信操作が失敗したときにエラーコードが割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイトオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 受信操作が失敗したときにエラーコードが割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 受信したデータが割り当てられるバイト配列。 |

### 戻り値

受信されたバイト数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |

### 戻り値

受信されたバイト数。

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) メソッド

ソケットからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 受信操作が失敗したときにエラーコードが割り当てられる出力パラメーター。 |

### 戻り値

受信されたバイト数。

## 参照

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)