---
title: TrimStart()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列の先頭からすべての空白文字を削除します。
type: docs
weight: 690
url: /ja/system/string/trimstart/
---
## String::TrimStart() const method

文字列の先頭からすべての空白文字を削除します。

```cpp
String System::String::TrimStart() const
```

### Return Value

[String](../)（先頭に空白がありません）

## String::TrimStart(char_t) const method

文字列の先頭から渡された文字のすべての出現を削除します。

```cpp
String System::String::TrimStart(char_t ch) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ch | char_t | 削除するシンボル。 |

### Return Value

削除結果。

## String::TrimStart(const String\&) const method

文字列の先頭から渡された文字のすべての出現を削除します。

```cpp
String System::String::TrimStart(const String &anyOf) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) 削除対象の文字。 |

### Return Value

[String](../)（削除された文字なし）

## String::TrimStart(const ArrayPtr\<char_t\>\&) const method

文字列の先頭から渡された文字のすべての出現を削除します。

```cpp
String System::String::TrimStart(const ArrayPtr<char_t> &anyOf) const
```

### Arguments

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) 削除対象の文字。 |

### Return Value

[String](../)（削除された文字なし）

## See Also

* 型定義 [ArrayPtr](../../arrayptr/)
* クラス [String](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)