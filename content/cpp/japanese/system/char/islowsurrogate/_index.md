---
title: IsLowSurrogate()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファ内の指定されたインデックスにある文字がロウサロゲートかどうかを判定します。
type: docs
weight: 53
url: /ja/system/char/islowsurrogate/
---
## Char::IsLowSurrogate(const char_t *, int) メソッド

指定された文字バッファ内の指定されたインデックスにある文字がロウサロゲートかどうかを判定します。

```cpp
static bool System::Char::IsLowSurrogate(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの開始位置へのポインタ |
| idx | int | 指定されたバッファ内でテスト対象の文字のゼロベースインデックス |

### 戻り値

指定されたインデックスの文字がロウサロゲートである場合は true、そうでない場合は false

## Char::IsLowSurrogate(char_t) メソッド

指定された文字がロウサロゲートかどうかを判定します。

```cpp
static bool System::Char::IsLowSurrogate(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字がロウサロゲートである場合は true、そうでない場合は false

## 参照

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)