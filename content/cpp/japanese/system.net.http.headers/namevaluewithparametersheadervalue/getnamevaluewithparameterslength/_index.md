---
title: GetNameValueWithParametersLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を NameValueWithParametersHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 92
url: /ja/system.net.http.headers/namevaluewithparametersheadervalue/getnamevaluewithparameterslength/
---
## NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド

[NameValueWithParametersHeaderValue](../) クラスのインスタンスに、指定されたインデックスから渡された文字列を変換します。

```cpp
static int32_t System::Net::Http::Headers::NameValueWithParametersHeaderValue::GetNameValueWithParametersLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析されたサブ文字列の長さを返し、そうでない場合は 0 を返します。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [NameValueWithParametersHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)