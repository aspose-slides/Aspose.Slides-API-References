---
title: IsSurrogatePair()
second_title: Aspose.Slides for C++ API リファレンス
description: UTF-16 サロゲートペアのために指定された 2 つの文字がペアかどうかを判定します。
type: docs
weight: 27
url: /ja/system/char/issurrogatepair/
---
## Char::IsSurrogatePair(char_t, char_t) メソッド

UTF-16 サロゲートペアのために指定された 2 つの文字がペアかどうかを判定します。

```cpp
static bool System::Char::IsSurrogatePair(char_t highSurrogate, char_t lowSurrogate)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| highSurrogate | char_t | 上位サロゲートかどうかテストされる文字 |
| lowSurrogate | char_t | 下位サロゲートかどうかテストされる文字 |

### 戻り値

指定された文字がサロゲートペアを構成している場合は true、それ以外の場合は false

## Char::IsSurrogatePair(const String\&, int) メソッド

指定された文字バッファ内の連続する 2 文字がサロゲートペアかどうかを判定します。

```cpp
static bool System::Char::IsSurrogatePair(const String &str, int index)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const [String](../../string/)\& | 文字列 |
| index | int | テスト対象の文字シーケンスが開始する、指定バッファ内の 0 基準インデックス |

### 戻り値

指定された文字がサロゲートペアを構成している場合は true、それ以外の場合は false

## 参照

* クラス [Char](../)
* クラス [String](../../string/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)