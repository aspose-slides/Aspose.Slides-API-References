---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現を含む）を、同等の 32 ビット符号なし整数に変換します。
type: docs
weight: 14
url: /ja/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の 32 ビット符号なし整数に変換します。

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| result | **uint32_t**\& | 変換結果が格納される 32 ビット符号なし整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false です。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の 32 ビット符号なし整数に変換します。

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 数値の文字列表現に許可されるスタイルを指定する NumberStyles 列挙体の値のビット単位の組み合わせ。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |
| result | **uint32_t**\& | 変換結果が格納される 32 ビット符号なし整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false です。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) メソッド




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) メソッド




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) メソッド




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)