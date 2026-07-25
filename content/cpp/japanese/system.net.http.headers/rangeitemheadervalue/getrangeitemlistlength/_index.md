---
title: GetRangeItemListLength()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された位置から渡された文字列を RangeItemHeaderValue クラスのインスタンスのコレクションに変換します。
type: docs
weight: 79
url: /ja/system.net.http.headers/rangeitemheadervalue/getrangeitemlistlength/
---
## RangeItemHeaderValue::GetRangeItemListLength(String, int32_t, System::SharedPtr\<Collections::Generic::ICollection\<System::SharedPtr\<RangeItemHeaderValue\>\>\>) method


指定された位置から渡された文字列を RangeItemHeaderValue クラスのインスタンスのコレクションに変換します。

```cpp
static int32_t System::Net::Http::Headers::RangeItemHeaderValue::GetRangeItemListLength(String input, int32_t startIndex, System::SharedPtr<Collections::Generic::ICollection<System::SharedPtr<RangeItemHeaderValue>>> rangeCollection)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | [String](../../../system/string/) | 解析対象の文字列。 |
| startIndex | **int32_t** | 解析の開始位置。 |
| rangeCollection | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<[System::SharedPtr](../../../system/sharedptr/)\<[RangeItemHeaderValue](../)\>\>\> | 解析されたコレクションが割り当てられるインスタンス。 |

### 戻り値

解析された部分文字列の長さ、そうでない場合は 0。

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [ICollection](../../../system.collections.generic/icollection/)
* クラス [RangeItemHeaderValue](../)
* 名前空間 [System::Net::Http::Headers](../../)
* ライブラリ [Aspose.Slides](../../../)