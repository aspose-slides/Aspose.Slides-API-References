---
title: IsSeparator()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字バッファの指定インデックスにある文字が区切り文字として分類されるかどうかを判定します。
type: docs
weight: 131
url: /ja/system/char/isseparator/
---
## Char::IsSeparator(const char_t *, int) メソッド

指定された文字バッファの指定インデックスにある文字が区切り文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsSeparator(const char_t *str, int idx)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | const char_t * | 文字バッファの開始位置を指すポインタ |
| idx | int | テスト対象の文字がある、指定バッファ内の 0 から始まるインデックス |

### 戻り値

指定されたインデックスにある文字が区切り文字である場合は True、そうでない場合は false

## Char::IsSeparator(char_t) メソッド

指定された文字が区切り文字として分類されるかどうかを判定します。

```cpp
static bool System::Char::IsSeparator(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | テスト対象の文字 |

### 戻り値

指定された文字が区切り文字である場合は True、そうでない場合は false

## 参照

* クラス [Char](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)