---
title: BeginWrite()
second_title: Aspose.Slides の C++ API リファレンス
description: 非同期書き込み操作を開始します。
type: docs
weight: 170
url: /ja/system.io/stream/beginwrite/
---
## Stream::BeginWrite(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) メソッド


非同期書き込み操作を開始します。

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 書き込むデータを含むバッファ |
| offset | int | **buffer** 内の0ベースのオフセットで、書き込むデータが開始する位置を示します |
| count | int | 書き込むバイト数 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 各非同期書き込み操作を一意に識別するためにユーザーが提供したデータ |

### Return Value

開始された非同期書き込み操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* Library [Aspose.Slides](../../../)