---
title: BeginGetResponse()
second_title: Aspose.Slides C++ 用 API リファレンス
description: リソースに対する非同期リクエストを開始します。
type: docs
weight: 274
url: /ja/system.net/webrequest/begingetresponse/
---
## WebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) メソッド

リソースに対する非同期リクエストを開始します。

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [WebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)