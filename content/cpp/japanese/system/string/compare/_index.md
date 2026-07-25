---
title: Compare()
second_title: Aspose.Slides for C++ API リファレンス
description: 2つのサブ文字列を大小比較します。
type: docs
weight: 820
url: /ja/system/string/compare/
---
## String::Compare(const String\&, int, const String\&, int, int, bool) メソッド

2つのサブ文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase=false)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| indexA | int | 最初の文字列部分文字列の開始位置。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| indexB | int | 2番目の文字列部分文字列の開始位置。 |
| length | int | 比較する文字数。 |
| ignoreCase | **bool** | 大文字と小文字を区別しないかどうかを指定します。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## String::Compare(const String\&, int, const String\&, int, int, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) メソッド

2つのサブ文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| indexA | int | 最初の文字列部分文字列の開始位置。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| indexB | int | 2番目の文字列部分文字列の開始位置。 |
| length | int | 比較する文字数。 |
| ignoreCase | **bool** | 大文字と小文字を区別しないかどうかを指定します。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 比較に使用するカルチャー。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## String::Compare(const String\&, const String\&, System::StringComparison) メソッド

2つの文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, const String &strB, System::StringComparison comparison_type)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## String::Compare(const String\&, int, const String\&, int, int, System::StringComparison) メソッド

2つの文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, int indexA, const String &strB, int indexB, int length, System::StringComparison comparison_type)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| indexA | int | 最初の文字列部分文字列の開始位置。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| indexB | int | 2番目の文字列部分文字列の開始位置。 |
| length | int | 比較する文字数。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## String::Compare(const String\&, const String\&, bool) メソッド

2つの文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase=false)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| ignoreCase | **bool** | 大文字と小文字を区別しないかどうかを指定します。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## String::Compare(const String\&, const String\&, bool, const SharedPtr\<System::Globalization::CultureInfo\>\&) メソッド

2つの文字列を大小比較します。

```cpp
static int System::String::Compare(const String &strA, const String &strB, bool ignoreCase, const SharedPtr<System::Globalization::CultureInfo> &ci)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| strA | const [String](../)\& | 比較対象の最初の文字列。 |
| strB | const [String](../)\& | 比較対象の2番目の文字列。 |
| ignoreCase | **bool** | 大文字と小文字を区別しないかどうかを指定します。 |
| ci | const [SharedPtr](../../sharedptr/)\<[System::Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 比較に使用するカルチャー。 |

### 戻り値

最初のサブ文字列が2番目より小さい場合は負の値、等しい場合は0、そうでない場合は正の値を返します。

## 参照

* Enum [StringComparison](../../stringcomparison/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)