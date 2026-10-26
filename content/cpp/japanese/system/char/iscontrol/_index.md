---
title: IsControl()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファの指定インデックスにある文字が Unicode 制御文字かどうかを判定します。
type: docs
weight: 66
url: /ja/system/char/iscontrol/
---
## Char::IsControl(const char_t *, int) メソッド

指定された文字バッファの指定インデックスにある文字が Unicode 制御文字かどうかを判定します。

```cpp
static bool System::Char::IsControl(const char_t *str, int idx)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの先頭へのポインタ |
| idx | int | テスト対象の文字があるバッファ内の0ベースインデックス |

### 戻り値

文字が Unicode 制御文字である場合は true、そうでない場合は false

## Char::IsControl(char_t) メソッド

指定された文字が Unicode 制御文字かどうかを判定します。

```cpp
static bool System::Char::IsControl(char_t c)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

文字が Unicode 制御文字である場合は true、そうでない場合は false

## 参照

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)