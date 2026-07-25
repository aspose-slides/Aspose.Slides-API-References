---
title: SendTo()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータを指定されたエンドポイントに送信します。
type: docs
weight: 651
url: /ja/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のオフセット（バイト単位）。 |
| size | **int32_t** | 'offset' パラメータから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のオフセット（バイト単位）。 |
| size | **int32_t** | 'offset' パラメータから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のオフセット（バイト単位）。 |
| size | **int32_t** | 'offset' パラメータから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| size | **int32_t** | 指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| size | **int32_t** | 指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| size | **int32_t** | 指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) メソッド


指定されたデータを指定されたエンドポイントに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |

### 戻り値

送信されたバイト数。

## 参照

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)