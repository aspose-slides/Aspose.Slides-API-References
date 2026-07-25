---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を NameValueWithParametersHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 79
url: /ja/system.net.http.headers/namevaluewithparametersheadervalue/tryparse/
---
## NameValueWithParametersHeaderValue::TryParse(String, System::SharedPtr\<NameValueWithParametersHeaderValue\>\&) メソッド

渡された文字列を [NameValueWithParametersHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::NameValueWithParametersHeaderValue::TryParse(String input, System::SharedPtr<NameValueWithParametersHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[NameValueWithParametersHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [NameValueWithParametersHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)