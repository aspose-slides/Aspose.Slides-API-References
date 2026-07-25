---
title: GetUnicode()
second_title: Aspose.Slides for C++ API リファレンス
description: ascii ドメイン名を Unicode 等価に変換します。
type: docs
weight: 92
url: /ja/system.globalization/idnmapping/getunicode/
---
## IdnMapping::GetUnicode(const String\&) const メソッド


[Convert](../../../system/convert/) ascii ドメイン名を Unicode 等価に変換します。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | 変換する [String](../../../system/string/)。 |

### 戻り値

ascii 文字列の Unicode 等価。

## IdnMapping::GetUnicode(const String\&, int) const メソッド


[Convert](../../../system/convert/) ascii ドメイン名を Unicode 等価に変換します。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | 変換する [String](../../../system/string/)。 |
| index | int | 変換する部分文字列の開始インデックス |

### 戻り値

ascii 文字列の Unicode 等価。

## IdnMapping::GetUnicode(const String\&, int, int) const メソッド


[Convert](../../../system/convert/) ascii ドメイン名を Unicode 等価に変換します。

```cpp
String System::Globalization::IdnMapping::GetUnicode(const String &ascii, int index, int count) const
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| ascii | const [String](../../../system/string/)\& | 変換する [String](../../../system/string/)。 |
| index | int | 変換する部分文字列の開始インデックス |
| count | int | 変換する文字数。 |

### 戻り値

ascii 文字列の Unicode 等価。

## 参照

* クラス [String](../../../system/string/)
* クラス [IdnMapping](../)
* 名前空間 [System::Globalization](../../)
* ライブラリ [Aspose.Slides](../../../)