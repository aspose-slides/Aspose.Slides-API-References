---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現）を、同等の 8 ビット符号なし整数に変換します。
type: docs
weight: 14
url: /ja/system/byte/tryparse/
---
## Byte::TryParse(const String\&, uint8_t\&) メソッド

指定された文字列（数値の文字列表現）を、同等の 8 ビット符号なし整数に変換します。

```cpp
static bool System::Byte::TryParse(const String &value, uint8_t &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| result | **uint8_t**\& | 変換結果が格納される 8 ビット符号なし整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false が返されます。

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint8_t\&) メソッド

指定された文字列（数値の文字列表現）を、提供された書式情報と数値スタイルを使用して、同等の 8 ビット符号なし整数に変換します。

```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint8_t &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値をビット単位で組み合わせたもので、文字列の数値表現に許可されるスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |
| result | **uint8_t**\& | 変換結果が格納される 8 ビット符号なし整数変数への参照。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false が返されます。

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint8_t\&) メソッド




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint8_t\&) メソッド




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint8_t &result)
```

## Byte::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint8_t\&) メソッド




```cpp
static bool System::Byte::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint8_t &result)
```

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Byte](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)