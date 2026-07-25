---
title: BeginSend()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期送信操作を開始します。
type: docs
weight: 495
url: /ja/system.net.sockets/socket/beginsend/
---
## Socket::BeginSend(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期送信操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginSend(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, AsyncCallback callback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データの読み取り元バッファ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 指定された配列の、'offset' パラメータから開始するバイト数。 |
| socketFlags | [SocketFlags](../../socketflags/) | 送信の動作。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期送信操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期送信操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 関連項目

* 列挙体 [SocketFlags](../../socketflags/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)