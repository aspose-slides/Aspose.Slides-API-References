---
title: IndexOfAny()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字の前方検索。
type: docs
weight: 638
url: /ja/system/string/indexofany/
---
## String::IndexOfAny(char_t, int) const メソッド


文字の前方検索。

```cpp
int System::String::IndexOfAny(char_t c, int startIndex=0) const
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | 検索対象の文字。 |
| startIndex | int | [Index](../../index/) 検索開始位置。 |

### 戻り値

[Index](../../index/) 最初の文字位置（startIndex 以降）または見つからなければ -1。

## String::IndexOfAny(const String\&, int) const メソッド


その結果、この文字列内で str のすべての文字を検索します。最初の文字が見つかった場合はその位置を返し、見つからなければ次の文字を検索し、以下同様です。

```cpp
int System::String::IndexOfAny(const String &str, int startIndex=0) const
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 検索対象の文字列。文字の順序は重要です。 |
| startIndex | int | 検索開始位置。 |

### 戻り値

[Index](../../index/) 最初に見つかった文字の位置、または見つからなければ -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&) const メソッド


文字列全体で渡された任意の文字を検索します。文字列の先頭文字を anyOf のすべての文字と比較し、次の文字でも同様に比較します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf) const
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 検索対象の文字。順序は関係ありません。 |

### 戻り値

[Index](../../index/) 最初に一致した文字の位置、または見つからなければ -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t) const メソッド


部分文字列内で渡された任意の文字を検索します。文字列の先頭文字を anyOf のすべての文字と比較し、次の文字でも同様に比較します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex) const
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 検索対象の文字。順序は関係ありません。 |
| startindex | **int32_t** | [Index](../../index/) 検索開始位置。 |

### 戻り値

[Index](../../index/) 最初に一致した文字の位置、または見つからなければ -1。

## String::IndexOfAny(const ArrayPtr\<char_t\>\&, int32_t, int32_t) const メソッド


部分文字列内で渡された任意の文字を検索します。文字列の先頭文字を anyOf のすべての文字と比較し、次の文字でも同様に比較します。最初に一致した文字のインデックスを返します。

```cpp
int System::String::IndexOfAny(const ArrayPtr<char_t> &anyOf, int32_t startindex, int32_t count) const
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 検索対象の文字。順序は関係ありません。 |
| startindex | **int32_t** | [Index](../../index/) 検索開始位置。 |
| count | **int32_t** | 検索対象となる文字数。 |

### 戻り値

[Index](../../index/) 最初に一致した文字の位置、または見つからなければ -1。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)