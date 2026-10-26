---
title: BeginConnect()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期接続操作を開始します。
type: docs
weight: 261
url: /ja/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | リモートホスト名。 |
| port | **int32_t** | リモートホストのポート。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期接続操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクト。

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | リモートホストのIPアドレス。 |
| port | **int32_t** | リモートホストのポート。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期接続操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクト。

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期接続操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | リモートホストのIPアドレス。 |
| port | **int32_t** | リモートホストのポート。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期接続操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期接続操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [TcpClient](../)
* クラス [IPAddress](../../../system.net/ipaddress/)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)