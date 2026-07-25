---
title: BeginRead()
second_title: Aspose.Slides for C++ API リファレンス
description: 非同期読み取り操作を開始します。
type: docs
weight: 417
url: /ja/system.net.security/sslstream/beginread/
---
## SslStream::BeginRead(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, AsyncCallback, System::SharedPtr\<Object\>) メソッド


非同期読み取り操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::Security::SslStream::BeginRead(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t count, AsyncCallback asyncCallback, System::SharedPtr<Object> asyncState) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | データを読み取るためのバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| count | **int32_t** | 読み取るバイト数。 |
| asyncCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| asyncState | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期読み取り操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期読み取り操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [SslStream](../)
* 名前空間 [System::Net::Security](../../)
* ライブラリ [Aspose.Slides](../../../)