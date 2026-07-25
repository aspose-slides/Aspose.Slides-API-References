---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を ContentRangeHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 157
url: /ja/system.net.http.headers/contentrangeheadervalue/tryparse/
---
## ContentRangeHeaderValue::TryParse(String, System::SharedPtr\<ContentRangeHeaderValue\>\&) メソッド

渡された文字列を [ContentRangeHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::ContentRangeHeaderValue::TryParse(String input, System::SharedPtr<ContentRangeHeaderValue> &parsedValue)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[ContentRangeHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

True が返されます（解析が正常に完了した場合）、それ以外の場合は false が返されます。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ContentRangeHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)