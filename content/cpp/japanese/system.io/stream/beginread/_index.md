---
title: BeginRead()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期読み取り操作を開始します。
type: docs
weight: 157
url: /ja/system.io/stream/beginread/
---
## Stream::BeginRead(System::ArrayPtr\<uint8_t\>, int, int, System::AsyncCallback, System::SharedPtr\<System::Object\>) メソッド

非同期読み取り操作を開始します。

```cpp
virtual System::SharedPtr<System::IAsyncResult> System::IO::Stream::BeginRead(System::ArrayPtr<uint8_t> buffer, int offset, int count, System::AsyncCallback callback, System::SharedPtr<System::Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み取り先のバッファ |
| offset | int | **buffer** 内の0ベースのオフセットで、読み取ったデータの書き込みを開始する位置を示します |
| count | int | 読み取るバイト数 |
| callback | [System::AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 各非同期読み取り操作を一意に識別するためにユーザーが提供するデータ |

### 戻り値

開始された非同期読み取り操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [Stream](../)
* 名前空間 [System::IO](../../)
* ライブラリ [Aspose.Slides](../../../)