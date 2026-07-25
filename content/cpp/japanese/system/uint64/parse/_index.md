---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号なし整数に変換します。
type: docs
weight: 1
url: /ja/system/uint64/parse/
---
## UInt64::Parse(const String\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |

### 戻り値

指定された文字列で表された数に等しい 64 ビット符号なし整数です。

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表された数に等しい 64 ビット符号なし整数です。

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の 64 ビット符号なし整数に変換します。

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙体の値のビット単位での組み合わせで、数値の文字列表現に許可されるスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表された数に等しい 64 ビット符号なし整数です。

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 構造体 [UInt64](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)