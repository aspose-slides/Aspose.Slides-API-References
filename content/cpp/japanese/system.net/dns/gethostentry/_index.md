---
title: GetHostEntry()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたホスト名またはIPアドレスを含む文字列を使用して、新しい IPHostEntry-class インスタンスを作成します。
type: docs
weight: 79
url: /ja/system.net/dns/gethostentry/
---
## Dns::GetHostEntry(String) メソッド

指定されたホスト名またはIPアドレスを含む文字列を使用して、新しい IPHostEntry-class インスタンスを作成します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(String hostNameOrAddress)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| hostNameOrAddress | [String](../../../system/string/) | ホスト名またはIPアドレスを含む文字列です。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンスです。

## Dns::GetHostEntry(System::SharedPtr\<IPAddress\>) メソッド

指定された IP アドレスを使用して、新しい IPHostEntry-class インスタンスを作成します。

```cpp
static System::SharedPtr<IPHostEntry> System::Net::Dns::GetHostEntry(System::SharedPtr<IPAddress> address)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../ipaddress/)\> | IP アドレスです。 |

### 戻り値

新しく作成された IPHostEntry-class インスタンスです。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IPHostEntry](../../iphostentry/)
* クラス [String](../../../system/string/)
* クラス [Dns](../)
* クラス [IPAddress](../../ipaddress/)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)