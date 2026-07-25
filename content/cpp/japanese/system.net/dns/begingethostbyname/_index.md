---
title: BeginGetHostByName()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホスト名を使用して、新しい IPHostEntry-class インスタンスを作成するための非同期操作を開始します。
type: docs
weight: 53
url: /ja/system.net/dns/begingethostbyname/
---
## Dns::BeginGetHostByName(String, AsyncCallback, System::SharedPtr\<Object\>) メソッド

指定されたホスト名を使用して、新しい IPHostEntry-class インスタンスを作成するための非同期操作を開始します。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostByName(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | ホスト名です。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバックです。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するために使用されるユーザー提供データです。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクトです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Class [IAsyncResult](../../../system/iasyncresult/)
* Class [String](../../../system/string/)
* Class [Object](../../../system/object/)
* Class [Dns](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)