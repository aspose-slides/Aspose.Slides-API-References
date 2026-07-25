---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API リファレンス
description: リソースにデータを書き込むためのストリームを取得する非同期操作を開始します。
type: docs
weight: 469
url: /ja/system.net/httpwebrequest/begingetrequeststream/
---
## HttpWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) メソッド

リソースにデータを書き込むためのストリームを取得する非同期操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::HttpWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するために使用されるユーザー提供のデータです。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトは、開始された非同期操作を表します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [HttpWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)