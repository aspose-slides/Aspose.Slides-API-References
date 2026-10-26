---
title: BeginGetRequestStream()
second_title: Aspose.Slides for C++ APIリファレンス
description: リソースにデータを書き込むためのストリームを取得する非同期操作を開始します。
type: docs
weight: 300
url: /ja/system.net/webrequest/begingetrequeststream/
---
## WebRequest::BeginGetRequestStream(AsyncCallback, System::SharedPtr\<Object\>) メソッド

リソースへのデータ書き込み用ストリームを取得するための非同期操作を開始します。

```cpp
virtual System::SharedPtr<IAsyncResult> System::Net::WebRequest::BeginGetRequestStream(AsyncCallback callback, System::SharedPtr<Object> state)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 非同期操作ごとに一意に識別するために使用されるユーザー提供のデータです。 |

### 戻り値

開始された非同期操作を表す[IAsyncResult](../../../system/iasyncresult/)オブジェクトです。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Object](../../../system/object/)
* クラス [WebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)