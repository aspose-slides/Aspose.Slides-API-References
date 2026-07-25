---
title: IsWhiteSpace()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファ内の指定インデックスにある文字が空白文字として分類されるかどうかを判定します。
type: docs
weight: 157
url: /ja/system/char/iswhitespace/
---
## Char::IsWhiteSpace(const char_t *, int) メソッド

指定された文字バッファ内の指定インデックスにある文字が空白文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsWhiteSpace(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの開始位置へのポインタ |
| idx | int | テスト対象文字のバッファ内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が空白文字である場合は True、そうでない場合は false

## Char::IsWhiteSpace(char_t) メソッド

指定された文字が空白文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsWhiteSpace(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字が空白文字である場合は True、そうでない場合は false

## Char::IsWhiteSpace(const String\&, int) メソッド

指定された文字列内の指定インデックスにある文字が空白文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsWhiteSpace(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 文字列 |
| index | int | 文字列内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が空白文字である場合は True、そうでない場合は false

## 参照

* クラス [Char](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)