---
title: ParseExact()
second_title: Aspose.Slides の C++ API リファレンス
description: 指定された日付と時刻の文字列表現を、指定された形式とカルチャ固有の書式情報を使用して同等の DateTime オブジェクトに変換します。文字列の形式は指定されたフォーマットと完全に一致している必要があります。変換に失敗した場合は例外がスローされます。
type: docs
weight: 872
url: /ja/system/datetime/parseexact/
---
## DateTime::ParseExact(const String&, const String&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) メソッド

指定された日付と時刻の文字列表現を、指定された形式とカルチャ固有の書式情報を使用して同等の [DateTime](../) オブジェクトに変換します。文字列の形式は指定されたフォーマットと完全に一致している必要があります。変換に失敗した場合は例外がスローされます。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)& | 変換対象となる日付と時刻の文字列表現です。 |
| format | const [String](../../string/)& | 文字列の形式です。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | カルチャ固有の書式情報を提供する [IFormatProvider](../../iformatprovider/) オブジェクトです。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列挙値のビット単位の組み合わせで、**s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供します。 |

### 戻り値

指定された文字列が表す日付と時刻の値に相当する [DateTime](../) クラスの新しいインスタンスです。

## DateTime::ParseExact(const String&, const String&, const SharedPtr<Globalization::CultureInfo>&, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String&, const String&, const SharedPtr<Globalization::DateTimeFormatInfo>&, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String&, const String&, std::nullptr_t, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<IFormatProvider>&, Globalization::DateTimeStyles) メソッド

指定された日付と時刻の文字列表現を、指定された形式群、カルチャ固有の書式情報、およびスタイルを使用して同等の [DateTime](../) オブジェクトに変換します。文字列の形式は指定された形式のいずれかと完全に一致している必要があります。変換に失敗した場合は例外がスローされます。

```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)& | 変換対象となる日付と時刻の文字列表現です。 |
| formats | const [ArrayPtr](../../arrayptr/)<[String](../../string/)>& | 文字列形式の配列です。 |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | カルチャ固有の書式情報を提供する [IFormatProvider](../../iformatprovider/) オブジェクトです。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列挙値のビット単位の組み合わせで、**s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供します。 |

### 戻り値

指定された文字列が表す日付と時刻の値に相当する [DateTime](../) クラスの新しいインスタンスです。

## DateTime::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<Globalization::CultureInfo>&, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String&, const ArrayPtr<String>&, const SharedPtr<Globalization::DateTimeFormatInfo>&, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles)
```

## DateTime::ParseExact(const String&, const ArrayPtr<String>&, std::nullptr_t, Globalization::DateTimeStyles) メソッド




```cpp
static DateTime System::DateTime::ParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles)
```

## See Also

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)