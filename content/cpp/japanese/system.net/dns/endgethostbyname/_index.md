---
title: EndGetHostByName()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された非同期操作が完了し、新しい IPHostEntry-class インスタンスが作成されるまで待機します。
type: docs
weight: 66
url: /ja/system.net/dns/endgethostbyname/
---
## Dns::EndGetHostByName(System::SharedPtr\<IAsyncResult\>) メソッド

指定された非同期操作が完了し、新しい IPHostEntry-class インスタンスが作成されるまで待機します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::EndGetHostByName(System::SharedPtr<IAsyncResult> asyncResult)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) オブジェクトで、非同期操作を表します。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンス。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPHostEntry](../../iphostentry/)
* クラス [IAsyncResult](../../../system/iasyncresult/)
* クラス [Dns](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)