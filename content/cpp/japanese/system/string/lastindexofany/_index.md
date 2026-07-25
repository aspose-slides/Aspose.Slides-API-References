---
title: LastIndexOfAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 渡された文字のいずれかを文字列全体で逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較する…という処理を繰り返します。最初に一致した文字のインデックスを返します。
type: docs
weight: 664
url: /ja/system/string/lastindexofany/
---
## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&) const method

渡された文字のいずれかを文字列全体で逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較する…という処理を繰り返します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)検索対象の文字。順序は関係ありません。 |

### 戻り値

[Index](../../index/)最後に一致した文字のインデックス、または見つからない場合は -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const method

渡された文字のいずれかを部分文字列で逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較する…という処理を繰り返します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)検索対象の文字。順序は関係ありません。 |
| startindex | **int32_t** | [Index](../../index/)検索開始位置。 |

### 戻り値

[Index](../../index/)最後に一致した文字のインデックス、または見つからない場合は -1。

## String::LastIndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const method

渡された文字のいずれかを部分文字列で逆方向に検索します。最後の文字を anyOf のすべての文字と比較し、次に前の文字を比較する…という処理を繰り返します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::LastIndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/)検索対象の文字。順序は関係ありません。 |
| startindex | **int32_t** | [Index](../../index/)検索開始位置。 |
| count | **int32_t** | 検索対象の文字数。 |

### 戻り値

[Index](../../index/)最後に一致した文字のインデックス、または見つからない場合は -1。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)