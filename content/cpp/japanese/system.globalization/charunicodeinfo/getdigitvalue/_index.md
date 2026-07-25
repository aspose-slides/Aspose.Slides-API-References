---
title: GetDigitValue()
second_title: Aspose.Slides for C++ APIリファレンス
description: 指定された文字の数字値を取得します。
type: docs
weight: 14
url: /ja/system.globalization/charunicodeinfo/getdigitvalue/
---
## CharUnicodeInfo::GetDigitValue(char16_t) メソッド

指定された文字の数字値を取得します。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(char16_t ch)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char16_t | Unicode 文字。 |

### 戻り値

指定された文字が数字でない場合は -1、そうでない場合は数字値が返されます。

## CharUnicodeInfo::GetDigitValue(const String\&, int) メソッド

文字列の指定されたインデックスにある文字の数字値を取得します。

```cpp
static int System::Globalization::CharUnicodeInfo::GetDigitValue(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | unicode 文字を含む文字列。 |
| index | int | unicode 文字のインデックス。 |

### 戻り値

指定された文字が数字でない場合は -1、そうでない場合は数字値が返されます。

## 参照

* クラス [CharUnicodeInfo](../)
* クラス [String](../../../system/string/)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)