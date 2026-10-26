---
title: GetRangeConditionLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を RangeConditionHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 105
url: /ja/system.net.http.headers/rangeconditionheadervalue/getrangeconditionlength/
---
## RangeConditionHeaderValue::GetRangeConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド

指定されたインデックスから渡された文字列を [RangeConditionHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::RangeConditionHeaderValue::GetRangeConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析された部分文字列の長さを返します。該当しない場合は0を返します。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [RangeConditionHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)