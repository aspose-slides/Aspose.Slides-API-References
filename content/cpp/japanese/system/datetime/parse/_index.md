---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻値の文字列表現を、同等の DateTime オブジェクトに変換します。
type: docs
weight: 859
url: /ja/system/datetime/parse/
---
## DateTime::Parse(const String\&) メソッド

指定された日付と時刻値の文字列表現を、同等の [DateTime](../) オブジェクトに変換します。

```cpp
static DateTime System::DateTime::Parse(const String &s)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象となる日付と時刻値の文字列表現。 |

### 戻り値

指定された文字列が表す日付と時刻値と等価な [DateTime](../) クラスの新しいインスタンスです。

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) メソッド

文化固有の書式情報を使用して、指定された日付と時刻値の文字列表現を同等の [DateTime](../) オブジェクトに変換します。

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象となる日付と時刻値の文字列表現。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) オブジェクトで、文化固有の書式情報を提供します。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | **s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供する列挙値のビット単位の組み合わせです。 |

### 戻り値

指定された文字列が表す日付と時刻値と等価な [DateTime](../) クラスの新しいインスタンスです。

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) メソッド

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) メソッド

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) メソッド

```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## 参照

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)