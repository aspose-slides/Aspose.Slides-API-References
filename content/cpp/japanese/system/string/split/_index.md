---
title: Split()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字で文字列を分割します。
type: docs
weight: 768
url: /ja/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const メソッド

文字で文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | char_t | 文字列を分割する文字。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(char_t, int32_t, StringSplitOptions) const メソッド

文字で文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | char_t | 文字列を分割する文字。 |
| count | **int32_t** | 返される部分文字列の最大数。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(char_t, char_t, StringSplitOptions) const メソッド

2つの文字のいずれかで文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separatorA | char_t | 文字列を分割する最初の文字。 |
| separatorB | char_t | 文字列を分割する2番目の文字。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const メソッド

指定された文字のいずれかで文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) の区切り文字。空の場合、任意の空白文字が区切り文字として扱われます。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const メソッド

指定された文字のいずれかで文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) の区切り文字。空の場合、任意の空白文字が区切り文字として扱われます。 |
| count | **int32_t** | 返される部分文字列の最大数。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const String\&, StringSplitOptions) const メソッド

部分文字列で文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | 区切りとして機能する部分文字列。空の場合、空白文字が区切り文字として機能します。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const String\&, int, StringSplitOptions) const メソッド

部分文字列で文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separator | const [String](../)\& | 区切りとして機能する部分文字列。空の場合、空白文字が区切り文字として機能します。 |
| count | int | 分割配列の要素数の最大値。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const メソッド

部分文字列で文字列を分割します。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) の区切り文字列。空の場合、分割は行われません。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const メソッド

部分文字列で文字列を分割します。現在、0 または 1 要素の区切り文字列配列のみサポートされています。

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) の区切り文字列。空の場合、分割は行われません。 |
| count | int | 分割配列の要素数の最大値。 |
| opt | [StringSplitOptions](../../stringsplitoptions/) | 分割オプション。 |

### 戻り値

[Array](../../array/) の部分文字列。

## 参照

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)