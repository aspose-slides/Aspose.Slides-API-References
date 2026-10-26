---
title: EndGetHostAddresses()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期操作が新しい IPHostEntry-class インスタンスを作成するまで待機します。
type: docs
weight: 144
url: /ja/system.net/dns/endgethostaddresses/
---
## Dns::EndGetHostAddresses(System::SharedPtr\<IAsyncResult\>) メソッド


指定された非同期操作が新しい IPHostEntry-class インスタンスを作成するまで待機します。

```cpp
static System::ArrayPtr<System::SharedPtr<IPAddress>> System::Net::Dns::EndGetHostAddresses(System::SharedPtr<IAsyncResult> asyncResult)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトは非同期操作を表します。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンス。

## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPAddress](../../ipaddress/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Dns](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)