---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を AuthenticationHeaderValue クラスのインスタンスに変換しようとしています。
type: docs
weight: 105
url: /ja/system.net.http.headers/authenticationheadervalue/tryparse/
---
## AuthenticationHeaderValue::TryParse(String, System::SharedPtr\<AuthenticationHeaderValue\>\&) メソッド


渡された文字列を [AuthenticationHeaderValue](../) クラスのインスタンスに変換しようとしています。

```cpp
static bool System::Net::Http::Headers::AuthenticationHeaderValue::TryParse(String input, System::SharedPtr<AuthenticationHeaderValue> &parsedValue)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[AuthenticationHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

True when the parsing is successfully done, otherwise false.

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [AuthenticationHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)