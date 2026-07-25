---
title: BeginGetResponse()
second_title: Aspose.Slides for C++ API リファレンス
description: リソースに対する非同期リクエストを開始します。
type: docs
weight: 170
url: /ja/system.net/filewebrequest/begingetresponse/
---
## FileWebRequest::BeginGetResponse(AsyncCallback, System::SharedPtr\<Object\>) メソッド


リソースに対して非同期リクエストを開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetResponse(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するために使用される、ユーザー提供のデータです。 |

### 戻り値

[IAsyncResult](../../../system/iasyncresult/) オブジェクトは、開始された非同期操作を表します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [FileWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)