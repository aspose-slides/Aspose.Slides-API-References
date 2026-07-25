---
title: ToUpper()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定された文字を大文字に変換します。
type: docs
weight: 222
url: /ja/system/char/toupper/
---
## Char::ToUpper(char_t) メソッド

指定された文字を大文字に変換します。

```cpp
static char_t System::Char::ToUpper(char_t c)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 変換する文字 |

### 戻り値

指定された文字が小文字の場合は大文字に変換した文字を返し、そうでない場合は元の文字を返します。

## Char::ToUpper(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド

指定された文字を大文字に変換します。

```cpp
static char_t System::Char::ToUpper(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 変換する文字 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | カルチャ固有の大文字小文字変換規則を提供するオブジェクト |

### 戻り値

指定された文字が小文字の場合は大文字に変換した文字を返し、そうでない場合は元の文字を返します。

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [Char](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)