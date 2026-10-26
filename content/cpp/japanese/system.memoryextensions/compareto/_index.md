---
title: CompareTo()
second_title: C++ 用 Aspose.Slides API リファレンス
description: 指定された文字列比較規則で 2 つの文字スパンを比較します。
type: docs
weight: 404
url: /ja/system.memoryextensions/compareto/
---
## System::MemoryExtensions::CompareTo(const ReadOnlySpan\<char16_t\>\&, const ReadOnlySpan\<char16_t\>\&, StringComparison) 関数

指定された文字列比較規則で 2 つの文字スパンを比較します。

```cpp
int32_t System::MemoryExtensions::CompareTo(const ReadOnlySpan<char16_t> &span, const ReadOnlySpan<char16_t> &other, StringComparison comparisonType)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 最初の文字スパン |
| other | const [ReadOnlySpan](../../system/readonlyspan/)\<char16_t\>\& | 2 番目の文字スパン |
| comparisonType | [StringComparison](../../system/stringcomparison/) | 実行する文字列比較の種類 |

### 戻り値

span < other の場合は負の値、等しい場合は 0、span > other の場合は正の値

## 参照

* 列挙型 [StringComparison](../../system/stringcomparison/)
* クラス [ReadOnlySpan](../../system/readonlyspan/)
* 名前空間 [System::MemoryExtensions](../)
* ライブラリ [Aspose.Slides](../../)