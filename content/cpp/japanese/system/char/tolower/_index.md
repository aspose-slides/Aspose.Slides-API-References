---
title: ToLower()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字を小文字に変換します。
type: docs
weight: 235
url: /ja/system/char/tolower/
---
## Char::ToLower(char_t) メソッド

指定された文字を小文字に変換します。

```cpp
static char_t System::Char::ToLower(char_t c)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 変換対象の文字 |

### 戻り値

指定された文字が大文字の場合は小文字に変換した文字を返し、そうでない場合は指定された文字を返します。

## Char::ToLower(char_t, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド

指定された文字を小文字に変換します。

```cpp
static char_t System::Char::ToLower(char_t c, const SharedPtr<Globalization::CultureInfo> &culture)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| c | char_t | 変換対象の文字 |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | 文化固有の大文字小文字変換規則を提供するオブジェクト。 |

### 戻り値

指定された文字が大文字の場合は小文字に変換した文字を返し、そうでない場合は指定された文字を返します。

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [Char](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)