---
title: BeginWrite()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期書き込み操作を開始します。
type: docs
weight: 274
url: /ja/system.net.sockets/networkstream/beginwrite/
---
## NetworkStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期書き込み操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 書き込むデータを含むバッファ。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 書き込むバイト数。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 非同期書き込み操作ごとに一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトは、開始された非同期書き込み操作を表します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)