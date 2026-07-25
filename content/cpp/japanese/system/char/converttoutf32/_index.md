---
title: ConvertToUtf32()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された UTF-16 サロゲートペアを UTF-32 のコード単位に変換します。
type: docs
weight: 287
url: /ja/system/char/converttoutf32/
---
## Char::ConvertToUtf32(char_t, char_t) メソッド

指定された UTF-16 サロゲートペアを UTF-32 のコード単位に変換します。

```cpp
static int System::Char::ConvertToUtf32(char_t highSurrogate, char_t lowSurrogate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| highSurrogate | char_t | 変換対象の UTF-16 サロゲートペアの上位サロゲート |
| lowSurrogate | char_t | 変換対象の UTF-16 サロゲートペアの下位サロゲート |

### 戻り値

変換結果として得られる UTF-32 のコード単位

## Char::ConvertToUtf32(const String\&, int) メソッド

文字列内の指定された位置にある UTF-16 エンコードされた文字またはサロゲートペアの値を UTF-32 のコード単位に変換します。

```cpp
static int System::Char::ConvertToUtf32(const String &s, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 文字またはサロゲートペアを含む文字列 |
| index | int | 指定された文字列内の文字またはサロゲートペアのインデックス位置 |

### 戻り値

変換結果として得られる UTF-32 のコード単位

## 参照

* クラス [Char](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)