---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリーム取得の非同期操作が完了するまで待機します。
type: docs
weight: 482
url: /ja/system.net/httpwebrequest/endgetrequeststream/
---
## HttpWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) メソッド

指定されたストリーム取得の非同期操作が完了するまで待機します。

```cpp
System::SharedPtr<IO::Stream> System::Net::HttpWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | ストリーム取得の非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクトです。 |

### 戻り値

リソースにデータを書き込むためのストリームです。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [HttpWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)