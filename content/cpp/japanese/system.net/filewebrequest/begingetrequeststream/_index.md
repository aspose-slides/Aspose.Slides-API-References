---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ API リファレンス
description: リソースにデータを書き込むためのストリームを取得する非同期操作を開始します。
type: docs
weight: 144
url: /ja/system.net/filewebrequest/begingetrequeststream/
---
## FileWebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) メソッド


リソースにデータを書き込むためのストリームを取得する非同期操作を開始します。

```cpp
System::SharedPtr<IAsyncResult> System::Net::FileWebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するためにユーザーが提供するデータです。 |

### 戻り値

開始された非同期操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクトです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [FileWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)