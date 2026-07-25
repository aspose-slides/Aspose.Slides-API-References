---
title: BeginGetHostEntry()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホスト名または IP アドレスを含む文字列を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。
type: docs
weight: 105
url: /ja/system.net/dns/begingethostentry/
---
## Dns::BeginGetHostEntry(String, AsyncCallback, System::SharedPtr\<Object\>) メソッド

指定されたホスト名または IP アドレスを含む文字列を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | ホスト名または IP アドレスを含む文字列。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## Dns::BeginGetHostEntry(System::SharedPtr\<IPAddress\>, AsyncCallback, System::SharedPtr\<Object\>) メソッド

指定された IP アドレスを使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostEntry(System::SharedPtr<IPAddress> address, AsyncCallback requestCallback, System::SharedPtr<Object> stateObject)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP アドレス。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| stateObject | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [Dns](../)
* クラス [IPAddress](../../ipaddress/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)