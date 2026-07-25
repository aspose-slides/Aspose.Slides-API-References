---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された数値の文字列表現を含む文字列を、同等の 8 ビット符号付き整数に変換します。
type: docs
weight: 14
url: /ja/system/sbyte/tryparse/
---
## SByte::TryParse(const String\&, int8_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の 8 ビット符号付き整数に変換します。

```cpp
static bool System::SByte::TryParse(const String &value, int8_t &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| result | **int8_t**\& | 変換結果が格納される 8 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int8_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して、同等の 8 ビット符号付き整数に変換します。

```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int8_t &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 数値の文字列表現の許容スタイルを指定する NumberStyles 列挙体の値のビットごとの組み合わせ。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |
| result | **int8_t**\& | 変換結果が格納される 8 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int8_t\&) メソッド




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int8_t\&) メソッド




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int8_t &result)
```

## SByte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int8_t\&) メソッド




```cpp
static bool System::SByte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int8_t &result)
```

## 関連項目

* 列挙体 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 構造体 [SByte](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)