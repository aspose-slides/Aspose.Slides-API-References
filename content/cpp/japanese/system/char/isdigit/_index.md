---
title: IsDigit()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定された文字バッファの指定インデックスにある文字が十進数字として分類されるかどうかを判定します。
type: docs
weight: 79
url: /ja/system/char/isdigit/
---
## Char::IsDigit(const char_t *, int) メソッド

指定された文字バッファの指定インデックスにある文字が十進数字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsDigit(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの開始位置へのポインタ |
| idx | int | テスト対象の文字があるバッファ内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が十進数字である場合は true、そうでない場合は false

## Char::IsDigit(const String\&, const int32_t) メソッド

指定された文字列の指定インデックスにある文字が十進数字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsDigit(const String &str, const int32_t idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 文字列 |
| idx | const **int32_t** | テスト対象の文字があるバッファ内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が十進数字である場合は true、そうでない場合は false

## Char::IsDigit(char_t) メソッド

指定された文字が十進数字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsDigit(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字が十進数字である場合は true、そうでない場合は false

## 参照

* クラス [Char](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)