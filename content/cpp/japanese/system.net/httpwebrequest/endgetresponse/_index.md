---
title: EndGetResponse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたリソースへの非同期リクエストが完了するまで待機します。
type: docs
weight: 508
url: /ja/system.net/httpwebrequest/endgetresponse/
---
## HttpWebRequest::EndGetResponse(System::SharedPtr\<IAsyncResult\>) メソッド


指定されたリソースへの非同期リクエストが完了するまで待機します。

```cpp
System::SharedPtr<WebResponse> System::Net::HttpWebRequest::EndGetResponse(System::SharedPtr<IAsyncResult> asyncResult) override
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは、リソースへの非同期リクエストを表します。 |

### 戻り値

Web レスポンスです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [WebResponse](../../webresponse/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [HttpWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)