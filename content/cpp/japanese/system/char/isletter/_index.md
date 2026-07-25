---
title: IsLetter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファ内の指定インデックスにある文字が Unicode 文字として分類されるかどうかを判断します。
type: docs
weight: 92
url: /ja/system/char/isletter/
---
## Char::IsLetter(const char_t *, int) メソッド

指定された文字バッファ内の指定インデックスにある文字が Unicode 文字として分類されるかどうかを判断します。

```cpp
static bool System::Char::IsLetter(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象の文字があるバッファ内のゼロベースインデックス |

### 戻り値

True if the character at the specified index is Unicode letter, otherwise - false

## Char::IsLetter(char_t) メソッド

指定された文字が Unicode 文字として分類されるかどうかを判断します。

```cpp
static bool System::Char::IsLetter(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

True if the specified character is Unicode letter, otherwise - false

## 参照

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)