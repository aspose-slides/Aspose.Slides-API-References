---
title: GetContentRangeLength()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された位置から渡された文字列を ContentRangeHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 170
url: /ja/system.net.http.headers/contentrangeheadervalue/getcontentrangelength/
---
## ContentRangeHeaderValue::GetContentRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド

指定された位置から渡された文字列を [ContentRangeHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::ContentRangeHeaderValue::GetContentRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析する文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが割り当てられるインスタンス。 |

### 戻り値

解析されたサブ文字列の長さ。該当しない場合は 0。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [ContentRangeHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)