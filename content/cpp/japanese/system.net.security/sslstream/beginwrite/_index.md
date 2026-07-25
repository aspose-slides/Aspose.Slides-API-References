---
title: BeginWrite()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期書き込み操作を開始します。
type: docs
weight: 443
url: /ja/system.net.security/sslstream/beginwrite/
---
## SslStream::BeginWrite(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド

非同期書き込み操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginWrite(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データを書き込むためのバイト配列です。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセットです。 |
| count | **int32_t** | 書き込むバイト数です。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期書き込み操作を一意に識別するためにユーザーが提供するデータです。 |

### 戻り値

開始された非同期書き込み操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクトです。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [SslStream](../)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)