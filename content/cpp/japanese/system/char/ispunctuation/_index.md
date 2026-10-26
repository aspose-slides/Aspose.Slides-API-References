---
title: IsPunctuation()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファ内の指定されたインデックスにある文字が句読点文字として分類されるかどうかを判定します。
type: docs
weight: 209
url: /ja/system/char/ispunctuation/
---
## Char::IsPunctuation(const char_t *, int) メソッド


指定された文字バッファ内の指定されたインデックスにある文字が句読点文字として分類されるかどうかを判断します。

```cpp
static bool System::Char::IsPunctuation(const char_t *str, int idx)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象の文字があるバッファ内のゼロベースインデックス |

### 戻り値

True if the character at the specified index is a punctuation character, otherwise - false

## Char::IsPunctuation(char_t) メソッド


指定された文字が句読点文字として分類されるかどうかを判断します。

```cpp
static bool System::Char::IsPunctuation(char_t c)
```


### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

True if the specified character is a punctuation character, otherwise - false

## 参照

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)