---
title: GetDecimalDigitValue()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字の10進数字の値を取得します。
type: docs
weight: 1
url: /ja/system.globalization/charunicodeinfo/getdecimaldigitvalue/
---
## CharUnicodeInfo::GetDecimalDigitValue(char16_t) メソッド

指定された文字の10進数字の値を取得します。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(char16_t ch)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char16_t | Unicode文字。 |

### 戻り値

10進数字の値、または指定された文字が10進数字でない場合は-1を返します。

## CharUnicodeInfo::GetDecimalDigitValue(const String\&, int) メソッド

文字列の指定されたインデックスにある文字の10進数字の値を取得します。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDecimalDigitValue(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | Unicode文字を含む文字列。 |
| index | int | Unicode文字のインデックス。 |

### 戻り値

10進数字の値、または指定された文字が10進数字でない場合は-1を返します。

## 参照

* クラス [CharUnicodeInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)