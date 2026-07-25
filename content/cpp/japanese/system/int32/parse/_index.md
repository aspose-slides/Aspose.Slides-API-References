---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 数値の文字列表現を含む指定された文字列を、同等の 32 ビット符号付き整数に変換します。
type: docs
weight: 1
url: /ja/system/int32/parse/
---
## Int32::Parse(const String\&) メソッド


指定された文字列（数値の文字列表現を含む）を、同等の 32 ビット符号付き整数に変換します。

```cpp
static int32_t System::Int32::Parse(const String &value)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット符号付き整数です。

## Int32::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド


指定された文字列（数値の文字列表現を含む）を、指定された書式情報を使用して同等の 32 ビット符号付き整数に変換します。

```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット符号付き整数です。

## Int32::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, std::nullptr_t) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, std::nullptr_t)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド


指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して同等の 32 ビット符号付き整数に変換します。

```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles enum の値のビット単位の組み合わせで、数値の文字列表現に許可されるスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表される数値に等しい 32 ビット符号付き整数です。

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int32::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static int32_t System::Int32::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, std::nullptr_t) メソッド




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, std::nullptr_t)
```

## Int32::Parse(const ReadOnlySpan\<char16_t\>\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド




```cpp
static int32_t System::Int32::Parse(const ReadOnlySpan<char16_t> &span, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Int32](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* クラス [ReadOnlySpan](../../readonlyspan/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)