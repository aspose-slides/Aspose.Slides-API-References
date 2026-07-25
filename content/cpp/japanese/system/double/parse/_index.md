---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現を含む）を、同等の倍精度浮動小数点値に変換します。
type: docs
weight: 1
url: /ja/system/double/parse/
---
## Double::Parse(const String\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Double::Parse(const String &value)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |

### 戻り値

指定された文字列で表される数値に等しい倍精度浮動小数点値。

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表される数値に等しい倍精度浮動小数点値。

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) メソッド




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報および数値スタイルを使用して同等の倍精度浮動小数点値に変換します。

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列挙型の値のビット単位の組み合わせで、数値の文字列表現に許可されたスタイルを指定します。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ。 |

### 戻り値

指定された文字列で表される数値に等しい倍精度浮動小数点値。

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 参照

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)