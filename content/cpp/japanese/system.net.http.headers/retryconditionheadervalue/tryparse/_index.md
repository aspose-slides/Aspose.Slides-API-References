---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字列を RetryConditionHeaderValue クラスのインスタンスに変換しようとします。
type: docs
weight: 92
url: /ja/system.net.http.headers/retryconditionheadervalue/tryparse/
---
## RetryConditionHeaderValue::TryParse(String, System::SharedPtr\<RetryConditionHeaderValue\>\&) メソッド

渡された文字列を [RetryConditionHeaderValue](../) クラスのインスタンスに変換しようとします。

```cpp
static bool System::Net::Http::Headers::RetryConditionHeaderValue::TryParse(String input, System::SharedPtr<RetryConditionHeaderValue> &parsedValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[RetryConditionHeaderValue](../)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析が正常に完了した場合は true、そうでない場合は false。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [RetryConditionHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)