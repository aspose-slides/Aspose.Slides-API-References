---
title: GetRangeLength()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定されたインデックスから渡された文字列を RangeHeaderValue クラスのインスタンスに変換します。
type: docs
weight: 118
url: /ja/system.net.http.headers/rangeheadervalue/getrangelength/
---
## RangeHeaderValue::GetRangeLength(String, int32_t, System::SharedPtr\<Object\>\&) メソッド


指定されたインデックスから渡された文字列を [RangeHeaderValue](../) クラスのインスタンスに変換します。

```cpp
static int32_t System::Net::Http::Headers::RangeHeaderValue::GetRangeLength(String input, int32_t startIndex, System::SharedPtr<Object> &parsedValue)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列です。 |
| startIndex | **int32_t** | 解析を開始する位置です。 |
| parsedValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 解析されたオブジェクトが代入されるインスタンスです。 |

### 戻り値

解析されたサブ文字列の長さを返します。取得できなければ 0 を返します。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [Object](../../../system/object/)
* クラス [RangeHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* Library [Aspose.Slides](../../../)