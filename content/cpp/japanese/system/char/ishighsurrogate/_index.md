---
title: IsHighSurrogate()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列の指定されたインデックスにある文字が UTF-16 の上位サロゲートコード単位かどうかを判定します。
type: docs
weight: 40
url: /ja/system/char/ishighsurrogate/
---
## Char::IsHighSurrogate(const String\&, int) メソッド

指定された文字列の指定されたインデックスにある文字が UTF-16 の上位サロゲートコード単位かどうかを判定します。

```cpp
static bool System::Char::IsHighSurrogate(const String &s, int index)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 文字列 |
| index | int | テスト対象の文字のインデックス |

### 戻り値

指定されたインデックスにある文字が UTF-16 の上位サロゲートコード単位である場合は True、そうでない場合は false

## Char::IsHighSurrogate(const char_t *, int) メソッド

指定された文字バッファの指定されたインデックスにある文字が上位サロゲートかどうかを判定します。

```cpp
static bool System::Char::IsHighSurrogate(const char_t *str, int idx)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象の文字のバッファ内のゼロベースインデックス |

### 戻り値

指定されたインデックスにある文字が上位サロゲートである場合は True、そうでない場合は false

## Char::IsHighSurrogate(char_t) メソッド

指定された文字が上位サロゲートかどうかを判定します。

```cpp
static bool System::Char::IsHighSurrogate(char_t c)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字が上位サロゲートである場合は True、そうでない場合は false

## 参照

* クラス [String](../../string/)
* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)