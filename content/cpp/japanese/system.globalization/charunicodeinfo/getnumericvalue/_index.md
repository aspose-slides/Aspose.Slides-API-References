---
title: GetNumericValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字に関連付けられた数値を取得します。
type: docs
weight: 27
url: /ja/system.globalization/charunicodeinfo/getnumericvalue/
---
## CharUnicodeInfo::GetNumericValue(char16_t) メソッド

指定された文字に関連付けられた数値を取得します。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(char16_t ch)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char16_t | Unicode 文字。 |

### 戻り値

数値、または指定された文字が数値文字でない場合は -1 を返します。

## CharUnicodeInfo::GetNumericValue(const String\&, int) メソッド

文字列の指定されたインデックスにある文字に関連付けられた数値を取得します。

```cpp
static double System::Globalization::CharUnicodeInfo::GetNumericValue(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Unicode 文字を含む文字列。 |
| index | int | Unicode 文字のインデックス。 |

### 戻り値

数値、または指定された文字が数値文字でない場合は -1 を返します。

## 参照

* クラス [CharUnicodeInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)