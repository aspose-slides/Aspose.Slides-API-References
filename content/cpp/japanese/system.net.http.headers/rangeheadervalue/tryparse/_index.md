---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を RangeHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 105
url: /ja/system.net.http.headers/rangeheadervalue/tryparse/
---
## RangeHeaderValue::TryParse(String, System::SharedPtr\<RangeHeaderValue\>\&) method


渡された文字列を [RangeHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::RangeHeaderValue::TryParse(String input, System::SharedPtr<RangeHeaderValue> &parsedValue)
```


### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RangeHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### Return Value

解析が正常に完了した場合は True、そうでない場合は false です。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [RangeHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)