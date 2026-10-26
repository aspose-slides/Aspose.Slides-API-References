---
title: GetStringComparer()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された CompareInfo オブジェクトと指定された文字列比較ルールに対して StringComparer オブジェクトを取得します。
type: docs
weight: 1
url: /ja/system.globalization/globalizationextensions/getstringcomparer/
---
## GlobalizationExtensions::GetStringComparer(const CompareInfoPtr\&, CompareOptions) メソッド

指定された [CompareInfo](../../compareinfo/) オブジェクトと指定された文字列比較ルールのための [StringComparer](../../../system/stringcomparer/) オブジェクトを取得します。

```cpp
static StringComparerPtr System::Globalization::GlobalizationExtensions::GetStringComparer(const CompareInfoPtr &compare_info, CompareOptions options)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| compare_info | const [CompareInfoPtr](../../compareinfoptr/)\& | [CompareInfo](../../compareinfo/) オブジェクト。 |
| options | [CompareOptions](../../compareoptions/) | [String](../../../system/string/) 比較オプション。 |

### 戻り値

[StringComparer](../../../system/stringcomparer/) オブジェクト。

## 参照

* 列挙体 [CompareOptions](../../compareoptions/)
* 型定義 [StringComparerPtr](../../../system/stringcomparerptr/)
* 型定義 [CompareInfoPtr](../../compareinfoptr/)
* クラス [GlobalizationExtensions](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)