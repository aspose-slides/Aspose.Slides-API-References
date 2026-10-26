---
title: Send()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたデータをソケットに送信します。
type: docs
weight: 638
url: /ja/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| size | **int32_t** | 指定されたデータから送信すべきバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| size | **int32_t** | 指定されたデータから送信すべきバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| size | **int32_t** | 指定されたデータから送信すべきバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::ArrayPtr\<uint8_t\>) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) メソッド


指定されたデータをソケットに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 送信すべきデータが含まれるバイト配列のコレクション。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 送信すべきデータが含まれるバイト配列のコレクション。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 送信すべきデータが含まれるバイト配列のコレクション。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 送信操作が失敗したときにエラーコードが代入される出力パラメーター。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) メソッド


指定されたデータをソケットに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 送信操作が失敗したときにエラーコードが代入される出力パラメーター。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) メソッド


指定されたデータをソケットに送信します。

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 送信操作が失敗したときにエラーコードが代入される出力パラメーター。 |

### 戻り値

送信されたバイト数。

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) メソッド


指定されたデータをソケットに送信します。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 送信するデータ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 'offset' パラメーターから始まる、指定された配列内のバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |
| errorCode | [SocketError](../../socketerror/)\& | 送信操作が失敗したときにエラーコードが代入される出力パラメーター。 |

### 戻り値

送信されたバイト数。

## 参照

* 列挙体 [SocketFlags](../../socketflags/)
* 列挙体 [SocketError](../../socketerror/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Socket](../)
* クラス [IList](../../../system.collections.generic/ilist/)
* クラス [ArraySegment](../../../system/arraysegment/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)