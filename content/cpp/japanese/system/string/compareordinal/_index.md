---
title: CompareOrdinal()
second_title: Aspose.Slides for C++ API リファレンス
description: オーディナルモードで 2 つの文字列を大小比較します。
type: docs
weight: 833
url: /ja/system/string/compareordinal/
---
## String::CompareOrdinal(const String\&, const String\&) メソッド

オーディナルモードで 2 つの文字列を大小比較します。

```cpp
static int System::String::CompareOrdinal(const String &strA, const String &strB)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較する最初の文字列。 |
| strB | const [String](../)\& | 比較する2番目の文字列。 |

### Return Value

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は 0、そうでない場合は正の値を返します。

## String::CompareOrdinal(const String\&, int, const String\&, int, int) メソッド

オーディナルモードで 2 つの文字列を大小比較します。

```cpp
static int System::String::CompareOrdinal(const String &strA, int indexA, const String &strB, int indexB, int length)
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較する最初の文字列。 |
| indexA | int | 最初の文字列サブ文字列の開始位置。 |
| strB | const [String](../)\& | 比較する2番目の文字列。 |
| indexB | int | 2番目の文字列サブ文字列の開始位置。 |
| length | int | 比較する文字数。 |

### Return Value

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は 0、そうでない場合は正の値を返します。

## 参照

* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)