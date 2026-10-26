---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: サブ文字列の前方検索。
type: docs
weight: 625
url: /ja/system/string/indexof/
---
## String::IndexOf(const String\&, System::StringComparison) const method

サブ文字列の前方検索。

```cpp
int System::String::IndexOf(const String &str, System::StringComparison comparison_type) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| str | const [String](../)\& | 検索対象のサブ文字列。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

最初に見つかったサブ文字列の [Index](../../index/)、見つからない場合は -1。検索文字列が空の場合は、常に 0 を返します。

## String::IndexOf(char_t, int) const method

文字の前方検索。

```cpp
int System::String::IndexOf(char_t c, int startIndex=0) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| c | char_t | 検索対象の文字。 |
| startIndex | int | [Index](../../index/) から検索を開始するインデックス。 |

### 戻り値

startIndex 以降の最初の文字位置の [Index](../../index/)、見つからない場合は -1。

## String::IndexOf(char_t, int, int) const method

サブ文字列内の文字の前方検索。

```cpp
int System::String::IndexOf(char_t c, int startIndex, int count) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| c | char_t | 検索対象の文字。 |
| startIndex | int | [Index](../../index/) から検索を開始するインデックス。 |
| count | int | 検索対象となる文字数。 |

### 戻り値

startIndex 以降の最初の文字位置の [Index](../../index/)、見つからない場合は -1。

## String::IndexOf(const String\&, int) const method

サブ文字列の前方検索。

```cpp
int System::String::IndexOf(const String &str, int startIndex=0) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| str | const [String](../)\& | 検索対象のサブ文字列。 |
| startIndex | int | 検索を開始するソース文字列内の位置。 |

### 戻り値

最初に見つかったサブ文字列の [Index](../../index/)、見つからない場合は -1。検索文字列が空の場合は、常に startIndex を返します。

## String::IndexOf(const String\&, int, System::StringComparison) const method

サブ文字列の前方検索。

```cpp
int System::String::IndexOf(const String &str, int startIndex, System::StringComparison comparison_type) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| str | const [String](../)\& | 検索対象のサブ文字列。 |
| startIndex | int | 検索を開始するソース文字列内の位置。 |
| comparison_type | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

最初に見つかったサブ文字列の [Index](../../index/)、見つからない場合は -1。検索文字列が空の場合は、常に startIndex を返します。

## String::IndexOf(const String\&, int, int, System::StringComparison) const method

サブ文字列の前方検索。

```cpp
int System::String::IndexOf(const String &value, int startIndex, int count, System::StringComparison comparisonType) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| value | const [String](../)\& | 検索対象のサブ文字列。 |
| startIndex | int | 検索を開始するソース文字列内の位置。 |
| count | int | 検索対象となる文字数。 |
| comparisonType | [System::StringComparison](../../stringcomparison/) | [Comparison](../../comparison/) モード。 |

### 戻り値

最初に見つかったサブ文字列の [Index](../../index/)、見つからない場合は -1。検索文字列が空の場合は、常に startIndex を返します。

## String::IndexOf(const String\&, int, int) const method

サブ文字列の前方検索。

```cpp
int System::String::IndexOf(const String &str, int startIndex, int count) const
```

### 引数

| パラメータ | 型 | 説明 |
|---|---|---|
| str | const [String](../)\& | 検索対象のサブ文字列。 |
| startIndex | int | 検索を開始するソース文字列内の位置。 |
| count | int | 検索対象となる文字数。 |

### 戻り値

最初に見つかったサブ文字列の [Index](../../index/)、見つからない場合は -1。検索文字列が空の場合は、常に startIndex を返します。

## 関連項目

* 列挙体 [StringComparison](../../stringcomparison/)
* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)