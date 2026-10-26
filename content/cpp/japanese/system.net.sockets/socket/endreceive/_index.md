---
title: EndReceive()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期受信操作が完了するまで待機します。
type: docs
weight: 534
url: /ja/system.net.sockets/socket/endreceive/
---
## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期受信操作が完了するまで待機します。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは非同期受信操作を表します。 |

### 戻り値

受信されたバイト数。

## Socket::EndReceive(System::SharedPtr\<IAsyncResult\>, SocketError\&) メソッド

指定された非同期受信操作が完了するまで待機します。

```cpp
int32_t System::Net::Sockets::Socket::EndReceive(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは非同期受信操作を表します。 |
| errorCode | [SocketError](../../socketerror/)\& | 受信操作が失敗したときにエラーコードが割り当てられる出力パラメータ。 |

### 戻り値

受信されたバイト数。

## 参照

* 列挙型 [SocketError](../../socketerror/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)