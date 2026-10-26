---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリソースへの非同期リクエストが完了するまで待機します。
type: docs
weight: 287
url: /ja/system.net/webrequest/endgetresponse/
---
## WebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) メソッド

指定されたリソースへの非同期リクエストが完了するまで待機します。

```cpp
virtual System::SharedPtr<WebResponse> System::Net::WebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは、リソースに対する非同期リクエストを表します。 |

### 返り値

Web 応答。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [WebResponse](../../webresponse/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [WebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)