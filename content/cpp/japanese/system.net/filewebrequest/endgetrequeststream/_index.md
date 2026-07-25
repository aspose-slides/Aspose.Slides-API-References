---
title: EndGetRequestStream()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたストリーム取得の非同期操作が完了するまで待機します。
type: docs
weight: 157
url: /ja/system.net/filewebrequest/endgetrequeststream/
---
## FileWebRequest::EndGetRequestStream(System::SharedPtr\<IAsyncResult\>) メソッド

指定されたストリーム取得の非同期操作が完了するまで待機します。

```cpp
System::SharedPtr<IO::Stream> System::Net::FileWebRequest::EndGetRequestStream(System::SharedPtr<IAsyncResult> asyncResult) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトで、ストリーム取得の非同期操作を表します。 |

### 戻り値

リソースにデータを書き込むためのストリームです。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Stream](../../../system.io/stream/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [FileWebRequest](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)