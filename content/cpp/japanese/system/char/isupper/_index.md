---
title: IsUpper()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列の指定されたインデックスにある文字が大文字かどうかを判定します。
type: docs
weight: 183
url: /ja/system/char/isupper/
---
## Char::IsUpper(const String&, int) メソッド

指定された文字列の指定されたインデックスにある文字が大文字かどうかを判断します。

```cpp
static bool System::Char::IsUpper(const String &str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)& | 文字を含む文字列。 |
| idx | int | テスト対象の文字列内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が大文字の場合は true、そうでない場合は false です。

## Char::IsUpper(const char_t *, int) メソッド

指定された文字バッファの指定されたインデックスにある文字が大文字かどうかを判断します。

```cpp
static bool System::Char::IsUpper(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象のバッファ内のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字が大文字の場合は true、そうでない場合は false です。

## Char::IsUpper(char_t) メソッド

指定された文字が大文字かどうかを判断します。

```cpp
static bool System::Char::IsUpper(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字が大文字の場合は true、そうでない場合は false です。

## 参照

* クラス [String](../../string/)
* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)