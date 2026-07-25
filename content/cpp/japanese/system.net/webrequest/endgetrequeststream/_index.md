---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリーム取得の非同期操作が完了するまで待機します。
type: docs
weight: 313
url: /ja/system.net/webrequest/endgetrequeststream/
---
## WebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期ストリーム取得操作が完了するまで待機します。

```cpp
virtual System::SharedPtr<IO::Stream> System::Net::WebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | ストリーム取得の非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクトです。 |

### 戻り値

リソースへデータを書き込むためのストリームです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [WebRequest](../)
* 名前空間 [System::Net](../../)
* Library [Aspose.Slides](../../../)