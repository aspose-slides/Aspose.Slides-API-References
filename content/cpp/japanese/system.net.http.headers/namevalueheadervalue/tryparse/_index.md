---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を NameValueHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 105
url: /ja/system.net.http.headers/namevalueheadervalue/tryparse/
---
## NameValueHeaderValue::TryParse(String, System::SharedPtr\<NameValueHeaderValue\>\&) method

渡された文字列を [NameValueHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::NameValueHeaderValue::TryParse(String input, System::SharedPtr<NameValueHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueHeaderValue](../)\>\& | 解析されたオブジェクトが代入されるインスタンス。 |

### 戻り値

解析が成功した場合は true、そうでない場合は false。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [NameValueHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)