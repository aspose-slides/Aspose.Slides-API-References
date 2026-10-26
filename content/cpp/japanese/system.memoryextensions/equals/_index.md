---
title: Equals()
second_title: Aspose.Slides for C++ API リファレンス
description: StringComparison を使用して、2つの ReadOnlySpan<char16_t> が等しいか比較します。
type: docs
weight: 417
url: /ja/system.memoryextensions/equals/
---
## System::MemoryExtensions::Equals(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数


StringComparison を使用して、2つの ReadOnlySpan<char16_t> が等しいか比較します。

```cpp
bool System::MemoryExtensions::Equals(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 比較する最初の span |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 比較する2番目の span |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 使用する文字列比較の種類 |

### 戻り値

spans が等しい場合は true、そうでない場合は false

## 参照

* 列挙型 [StringComparison](../../system/stringcomparison/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)