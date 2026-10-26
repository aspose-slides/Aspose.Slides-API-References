---
title: TryParseExact()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォーマット、カルチャ固有の書式情報、スタイルを使用して、指定された日時値の文字列表現を同等の DateTime オブジェクトに変換します。文字列表現のフォーマットは、指定されたフォーマットと完全に一致している必要があります。
type: docs
weight: 898
url: /ja/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


指定された日時値の文字列表現を、指定されたフォーマット、カルチャ固有の書式情報、およびスタイルを使用して同等の [DateTime](../) オブジェクトに変換します。文字列表現のフォーマットは、指定されたフォーマットと完全に一致する必要があります。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象の日時値の文字列表現。 |
| format | const [String](../../string/)\& | 文字列のフォーマット。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) オブジェクトは、カルチャ固有の書式情報を提供します。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | ビット単位の組み合わせで、列挙値が **s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供します。 |
| result | [DateTime](../)\& | 変換が成功した場合に変換結果を格納する出力引数。 |

### 戻り値

変換が成功すれば true、そうでなければ - false。

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method


指定された日時値の文字列表現を、指定されたフォーマットの配列、カルチャ固有の書式情報、およびスタイルを使用して同等の [DateTime](../) オブジェクトに変換します。文字列表現のフォーマットは、指定されたフォーマットのいずれかと完全に一致する必要があります。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象の日時値の文字列表現。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 文字列フォーマットの配列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | [IFormatProvider](../../iformatprovider/) オブジェクトは、カルチャ固有の書式情報を提供します。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | ビット単位の組み合わせで、列挙値が **s** に関する追加情報、**s** に存在する可能性のあるスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供します。 |
| result | [DateTime](../)\& | 変換が成功した場合に変換結果を格納する出力引数。 |

### 戻り値

変換が成功すれば true、そうでなければ - false。

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 参照

* Enum [DateTimeStyles](../../../system.globalization/datetimestyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [DateTime](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)