---
title: BeginConnect()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期接続操作を開始します。
type: docs
weight: 573
url: /ja/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | リモートエンドポイント。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するために使用されるユーザー提供データ。 |

### 戻り値

開始された非同期接続操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| host | [String](../../../system/string/) | リモートホスト名。 |
| port | **int32_t** | リモートホストのポート番号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するために使用されるユーザー提供データ。 |

### 戻り値

開始された非同期接続操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | リモートホストの IP アドレス。 |
| port | **int32_t** | リモートホストのポート番号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するために使用されるユーザー提供データ。 |

### 戻り値

開始された非同期接続操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | リモートホストの IP アドレス。 |
| port | **int32_t** | リモートホストのポート番号。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するために使用されるユーザー提供データ。 |

### 戻り値

開始された非同期接続操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [EndPoint](../../../system.net/endpoint/)
* クラス [Object](../../../system/object/)
* クラス [Socket](../)
* クラス [String](../../../system/string/)
* クラス [IPAddress](../../../system.net/ipaddress/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)