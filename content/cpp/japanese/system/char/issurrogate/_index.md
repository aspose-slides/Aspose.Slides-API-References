---
title: IsSurrogate()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字が UTF-16 サロゲートコードユニットであるかどうかを判断します。
type: docs
weight: 14
url: /ja/system/char/issurrogate/
---
## Char::IsSurrogate(char_t) メソッド

指定された文字が UTF-16 サロゲートコードユニットであるかどうかを判断します。

```cpp
static bool System::Char::IsSurrogate(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 文字 |

### 戻り値

指定された文字が UTF-16 サロゲートコードユニットである場合は true、そうでない場合は false

## Char::IsSurrogate(const String\&, int) メソッド

指定された文字列の指定されたインデックスにある文字が UTF-16 サロゲートコードユニットであるかどうかを判断します。

```cpp
static bool System::Char::IsSurrogate(const String &s, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 文字列 |
| index | int | 指定された文字列における文字のインデックス |

### 戻り値

指定されたインデックスの文字が UTF-16 サロゲートコードユニットである場合は true、そうでない場合は false

## 参照

* クラス [Char](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)