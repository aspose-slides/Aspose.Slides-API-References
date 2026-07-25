---
title: BeginResolve()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホスト名を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。
type: docs
weight: 157
url: /ja/system.net/dns/beginresolve/
---
## Dns::BeginResolve(String, AsyncCallback, System::SharedPtr\<Object\>) メソッド

指定されたホスト名を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginResolve(String hostName, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hostName | [String](../../../system/string/) | [IPHostEntry](../../iphostentry/) クラスの新しいインスタンスを作成するために使用されるホスト名です。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了した時に呼び出されるコールバックです。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するために使用されるユーザー提供のデータです。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクトです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [Dns](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)