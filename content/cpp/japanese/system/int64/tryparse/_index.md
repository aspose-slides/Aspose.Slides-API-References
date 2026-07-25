---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号付き整数に変換します。
type: docs
weight: 14
url: /ja/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号付き整数に変換します。

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| result | **int64_t**\& | 変換結果を格納する 64 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して、同等の 64 ビット符号付き整数に変換します。

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体のビット単位の組み合わせで、数値文字列表現に許可されるスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |
| result | **int64_t**\& | 変換結果を格納する 64 ビット符号付き整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) メソッド




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) メソッド




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) メソッド




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## 参照

* 列挙体 [NumberStyles](../../../system.globalization/numberstyles/)
* typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Int64](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)