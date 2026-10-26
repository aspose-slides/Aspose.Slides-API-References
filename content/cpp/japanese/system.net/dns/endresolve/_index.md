---
title: EndResolve()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期操作が新しい IPHostEntry-class インスタンスの作成を完了するまで待機します。
type: docs
weight: 170
url: /ja/system.net/dns/endresolve/
---
## Dns::EndResolve(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期操作が新しい IPHostEntry-class インスタンスの作成を完了するまで待機します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndResolve(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 非同期操作を表す [IAsyncResult](../../../system/iasyncresult/) オブジェクトです。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンスです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPHostEntry](../../iphostentry/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Dns](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)