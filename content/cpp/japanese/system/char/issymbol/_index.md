---
title: IsSymbol()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファ内の指定されたインデックスにある文字がシンボル文字として分類されるかどうかを判定します。
type: docs
weight: 144
url: /ja/system/char/issymbol/
---
## Char::IsSymbol(const char_t *, int) メソッド

指定された文字バッファ内の指定されたインデックスにある文字がシンボル文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsSymbol(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象の文字があるバッファ内の 0 基準インデックス |

### 戻り値

文字がシンボル文字である場合は True、そうでない場合は false

## Char::IsSymbol(char_t) メソッド

指定された文字がシンボル文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsSymbol(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

文字がシンボル文字である場合は True、そうでない場合は false

## 関連項目

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)