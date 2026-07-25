---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列をビルダーの固定位置に挿入します。
type: docs
weight: 183
url: /ja/system.text/stringbuilder/insert/
---
## StringBuilder::Insert(int, const String\&) メソッド

文字列をビルダーの固定位置に挿入します。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, const String &str)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 文字を挿入する位置。 |
| str | const [String](../../../system/string/)\& | [String](../../../system/string/) を挿入します。 |

### 戻り値

このポインタ。

## StringBuilder::Insert(int32_t, const String\&, int32_t) メソッド

繰り返し文字列をビルダーの固定位置に挿入します。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int32_t index, const String &value, int32_t count)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | 文字を挿入する位置。 |
| value | const [String](../../../system/string/)\& | [String](../../../system/string/) を挿入します。 |
| count | **int32_t** | **value** 文字列を繰り返す回数。 |

### 戻り値

このポインタ。

## StringBuilder::Insert(int, char_t) メソッド

文字をビルダーの固定位置に挿入します。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int startIndex, char_t ch)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 文字を挿入する位置。 |
| ch | char_t | 挿入する文字。 |

### 戻り値

このポインタ。

## StringBuilder::Insert(int, const System::ArrayPtr\<char_t\>\&, int, int) メソッド

文字列をビルダーの固定位置に挿入します。

```cpp
StringBuilder * System::Text::StringBuilder::Insert(int index, const System::ArrayPtr<char_t> &chars, int startIndex, int charCount)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| index | int | 文字を挿入する位置。 |
| chars | const [System::ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | [Array](../../../system/array/) からスライスを挿入します。 |
| startIndex | int | [Array](../../../system/array/) スライス開始インデックス。 |
| charCount | int | [Array](../../../system/array/) スライス長さ。 |

### 戻り値

このポインタ。

## StringBuilder::Insert(int, T) メソッド

値をビルダーの固定位置に挿入します。

```cpp
template<typename T> std::enable_if<std::is_arithmetic<T>::value, StringBuilder *>::type System::Text::StringBuilder::Insert(int startIndex, T value)
```

### テンプレート パラメータ

| パラメータ | 説明 |
| --- | --- |
| Parameter | 型。 |

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| startIndex | int | 文字を挿入する位置。 |
| value | T | フォーマットして挿入する値。 |

### 戻り値

このポインタ。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [StringBuilder](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)