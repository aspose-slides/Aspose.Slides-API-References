---
title: GetAuthenticationLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列を解析し、文字列表現の最後のインデックスを返します。
type: docs
weight: 118
url: /ja/system.net.http.headers/authenticationheadervalue/getauthenticationlength/
---
## AuthenticationHeaderValue::GetAuthenticationLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド

指定された文字列を解析し、文字列表現の最後のインデックスを返します。

```cpp
static int32_t System::Net::Http::Headers::AuthenticationHeaderValue::GetAuthenticationLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析が必要な文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析された値が代入される出力パラメータ。 |

### 戻り値

解析された部分文字列の長さ、そうでなければ 0。

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [AuthenticationHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)