---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された文字列（数値の文字列表現を含む）を、同等の単精度浮動小数点値に変換します。
type: docs
weight: 1
url: /ja/system/single/parse/
---
## Single::Parse(const String\&) メソッド

指定された文字列（数値の文字列表現を含む）を、同等の単精度浮動小数点値に変換します。

```cpp
static float System::Single::Parse(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列です。 |

### 戻り値

指定された文字列で表される数値に等しい単精度浮動小数点値です。

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報を使用して、同等の単精度浮動小数点値に変換します。

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列です。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタです。 |

### 戻り値

指定された文字列で表される数値に等しい単精度浮動小数点値です。

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) メソッド




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された文字列（数値の文字列表現を含む）を、提供された書式情報と数値スタイルを使用して、同等の単精度浮動小数点値に変換します。

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換対象の文字列です。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 数値の文字列表現に許可されたスタイルを指定する NumberStyles 列挙体の値のビット単位の組み合わせです。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタです。 |

### 戻り値

指定された文字列で表される数値に等しい単精度浮動小数点値です。

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) メソッド




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) メソッド




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## 参照

* 列挙型 [NumberStyles](../../../system.globalization/numberstyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 構造体 [Single](../)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)