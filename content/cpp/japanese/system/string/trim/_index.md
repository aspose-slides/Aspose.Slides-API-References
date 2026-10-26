---
title: Trim()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の先頭と末尾からすべての空白文字を削除します。
type: docs
weight: 677
url: /ja/system/string/trim/
---
## String::Trim() const メソッド


文字列の先頭と末尾からすべての空白文字を削除します。

```cpp
String System::String::Trim() const
```


### 戻り値

[String](../) 先頭または末尾に空白がありません。

## String::Trim(char_t) const メソッド


文字列の先頭と末尾から渡された文字のすべての出現を削除します。

```cpp
String System::String::Trim(char_t ch) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char_t | 削除するシンボル。 |

### 戻り値

削除結果。

## String::Trim(const String\&) const メソッド


文字列の先頭と末尾から渡された文字のすべての出現を削除します。

```cpp
String System::String::Trim(const String &anyOf) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 削除する文字の集合。 |

### 戻り値

[String](../) 削除された文字がありません。

## String::Trim(const ArrayPtr\<char_t\>\&) const メソッド


文字列の先頭と末尾から渡された文字のすべての出現を削除します。

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 削除する文字の集合。 |

### 戻り値

[String](../) 削除された文字がありません。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)