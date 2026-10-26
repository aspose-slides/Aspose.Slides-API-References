---
title: BeginRead()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 非同期読み取り操作を開始します。
type: docs
weight: 248
url: /ja/system.net.sockets/networkstream/beginread/
---
## NetworkStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期読み取り操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::NetworkStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 読み取ったバイトを書き込むバイト配列です。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセットです。 |
| size | **int32_t** | 読み取るバイト数です。 |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期読み取り操作を一意に識別するためにユーザーが提供するデータです。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトは、開始された非同期読み取り操作を表します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [NetworkStream](../)
* 名前空間 [System::Net::Sockets](../../)
* ライブラリ [Aspose.Slides](../../../)