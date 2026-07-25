---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: オブジェクトが表す値の文字列表現を返します。
type: docs
weight: 352
url: /ja/system/decimal/tostring/
---
## Decimal::ToString() const メソッド

オブジェクトが表す値の文字列表現を返します。

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const メソッド

現在のオブジェクトを、文化固有の書式情報を使用して文字列に変換します。

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文化固有の書式情報を提供する [IFormatProvider](../../iformatprovider/) オブジェクト。 |

### 戻り値

現在のオブジェクトの文字列表現。

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const メソッド

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const メソッド

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const メソッド

現在のオブジェクトを、指定された文字列形式と、指定された [IFormatProvider](../../iformatprovider/) オブジェクトが提供する文化固有の書式情報を使用して文字列表現に変換します。

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 文字列形式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文化固有の書式情報を提供する [IFormatProvider](../../iformatprovider/) オブジェクト。 |

### 戻り値

現在のオブジェクトの文字列表現。

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const メソッド

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const メソッド

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [Decimal](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)