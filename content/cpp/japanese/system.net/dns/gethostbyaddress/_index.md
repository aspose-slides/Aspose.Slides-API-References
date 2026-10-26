---
title: GetHostByAddress()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された IP アドレスの文字列表現を使用して、新しい IPHostEntry-class インスタンスを作成します。
type: docs
weight: 14
url: /ja/system.net/dns/gethostbyaddress/
---
## Dns::GetHostByAddress(String) メソッド

指定された IP アドレスの文字列表現を使用して、新しい IPHostEntry-class インスタンスを作成します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(String address)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | [String](../../../system/string/) | IP アドレスの文字列表現です。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンスです。

## Dns::GetHostByAddress(System::SharedPtr\<IPAddress\>) メソッド

指定された IP アドレスを使用して、新しい IPHostEntry-class インスタンスを作成します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostByAddress(System::SharedPtr<IPAddress> address)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP アドレスです。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンスです。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IPHostEntry](../../iphostentry/)
* クラス [String](../../../system/string/)
* クラス [Dns](../)
* クラス [IPAddress](../../ipaddress/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)