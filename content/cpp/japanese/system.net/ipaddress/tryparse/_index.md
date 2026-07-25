---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を IPAddress クラスのインスタンスに変換しようとします。
type: docs
weight: 222
url: /ja/system.net/ipaddress/tryparse/
---
## IPAddress::TryParse(String, System::SharedPtr\<IPAddress\>\&) メソッド

渡された文字列を [IPAddress](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::IPAddress::TryParse(String ipString, System::SharedPtr<IPAddress> &address)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ipString | [String](../../../system/string/) | 解析する文字列。 |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が成功した場合は true、そうでない場合は false。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IPAddress](../)
* 名前空間 [System::Net](../../)
* ライブラリ [Aspose.Slides](../../../)