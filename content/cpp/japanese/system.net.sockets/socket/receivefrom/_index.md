---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。
type: docs
weight: 690
url: /ja/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| size | **int32_t** | 'offset' インデックスから指定されたバイト配列に割り当てられる受信バイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) method


指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモートエンドポイント。 |

### 戻り値

受信したバイト数。

## 参照

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)