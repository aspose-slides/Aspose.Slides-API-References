---
title: TrimEnd()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の末尾からすべての空白文字を削除します。
type: docs
weight: 703
url: /ja/system/string/trimend/
---
## String::TrimEnd() const メソッド

文字列の末尾からすべての空白文字を削除します。

```cpp
String System::String::TrimEnd() const
```

### 戻り値

[String](../) 先頭の空白がありません。

## String::TrimEnd(char_t) const メソッド

文字列の末尾から渡された文字をすべて削除します。

```cpp
String System::String::TrimEnd(char_t ch) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char_t | 削除するシンボル。 |

### 戻り値

削除結果。

## String::TrimEnd(const String\&) const メソッド

文字列の末尾から渡された文字のすべての出現を削除します。

```cpp
String System::String::TrimEnd(const String &anyOf) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 削除対象の文字。 |

### 戻り値

[String](../) 削除された文字なし。

## String::TrimEnd(const ArrayPtr\<char_t\>\&) const メソッド

文字列の末尾から渡された文字のすべての出現を削除します。

```cpp
String System::String::TrimEnd(const ArrayPtr<char_t> &anyOf) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 削除対象の文字。 |

### 戻り値

[String](../) 削除された文字なし。

## 参照

* Typedef [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)