---
title: EndSend()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期送信操作が完了するまで待機します。
type: docs
weight: 508
url: /ja/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期送信操作が完了するまで待機します。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 非同期送信操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。 |

### 戻り値

送信されたバイト数。

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) メソッド

指定された非同期送信操作が完了するまで待機します。

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 非同期送信操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。 |
| errorCode | [SocketError](../../socketerror/)\& | 送信操作が失敗した際にエラーコードが代入される出力パラメータ errorCode。 |

### 戻り値

送信されたバイト数。

## 参照

* 列挙型 [SocketError](../../socketerror/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)