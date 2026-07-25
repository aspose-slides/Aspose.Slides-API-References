---
title: BeginGetHostAddresses()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（ホスト名またはIPアドレスを含む）を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。
type: docs
weight: 131
url: /ja/system.net/dns/begingethostaddresses/
---
## Dns::BeginGetHostAddresses(String, AsyncCallback, System::SharedPtr\<Object\>) メソッド


指定された文字列（ホスト名またはIPアドレスを含む）を使用して、新しい IPHostEntry-class インスタンスを作成する非同期操作を開始します。

```cpp
static System::SharedPtr<IAsyncResult> System::Net::Dns::BeginGetHostAddresses(String hostNameOrAddress, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | ホスト名またはIPアドレスを含む文字列。 |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | 操作が完了したときに呼び出されるコールバック。 |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 各非同期操作を一意に識別するためにユーザーが提供するデータ。 |

### 戻り値

開始された非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクト。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [AsyncCallback](../../../system/asynccallback/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [Dns](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)