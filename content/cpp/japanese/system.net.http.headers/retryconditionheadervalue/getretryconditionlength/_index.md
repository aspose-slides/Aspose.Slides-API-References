---
title: GetRetryConditionLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたインデックスから渡された文字列を RetryConditionHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 105
url: /ja/system.net.http.headers/retryconditionheadervalue/getretryconditionlength/
---
## RetryConditionHeaderValue::GetRetryConditionLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド


指定されたインデックスから渡された文字列を [RetryConditionHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::RetryConditionHeaderValue::GetRetryConditionLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列です。 |
| startIndex | **int32_t** | 解析の開始位置です。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが割り当てられるインスタンスです。 |

### 戻り値

解析されたサブ文字列の長さを返し、そうでない場合は 0 を返します。

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [RetryConditionHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)