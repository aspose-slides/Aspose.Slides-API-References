---
title: BeginReceive()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期の書き込み操作を開始します。
type: docs
weight: 521
url: /ja/system.net.sockets/socket/beginreceive/
---
## Socket::BeginReceive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期の書き込み操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginReceive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバッファ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 指定された配列の、'offset' パラメータから開始するバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 受信の動作。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期受信操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期受信操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 参照

* Enum [SocketFlags](../../socketflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)