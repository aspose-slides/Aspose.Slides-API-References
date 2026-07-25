---
title: TryParseExact()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたフォーマットとフォーマットプロバイダーを使用して文字列を同等の TimeSpan オブジェクトに変換し、変換結果を返します。
type: docs
weight: 573
url: /ja/system/timespan/tryparseexact/
---
## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) メソッド

指定されたフォーマットとフォーマットプロバイダーを使用して文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) のフォーマット文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | カルチャ固有の書式情報を提供するフォーマットプロバイダー。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列の変換が成功した場合は true、そうでない場合は false が返されます。

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

指定されたフォーマット、フォーマットプロバイダー、およびスタイルを使用して文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| format | const [String](../../string/)\& | 標準またはカスタムの書式文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | カルチャ固有の書式情報を提供するフォーマットプロバイダー。 |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 入力文字列に存在しえる要素を定義します。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列の変換が成功した場合は true、そうでない場合は false が返されます。

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

指定されたフォーマット、フォーマットプロバイダー、およびスタイルを使用して文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | [Array](../../array/) のフォーマット文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | カルチャ固有の書式情報を提供するフォーマットプロバイダー。 |
| styles | [Globalization::TimeSpanStyles](../../../system.globalization/timespanstyles/) | 入力文字列に存在しえる要素を定義します。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列の変換が成功した場合は true、そうでない場合は false が返されます。

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::TimeSpanStyles, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::TimeSpanStyles styles, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) メソッド

指定されたフォーマットとフォーマットプロバイダーを使用して文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| format | const [String](../../string/)\& | 標準またはカスタムの書式文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | カルチャ固有の書式情報を提供するフォーマットプロバイダー。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列の変換が成功した場合は true、そうでない場合は false が返されます。

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParseExact(const String\&, const String\&, std::nullptr_t, TimeSpan\&) メソッド

```cpp
static bool System::TimeSpan::TryParseExact(const String &input, const String &format, std::nullptr_t, TimeSpan &result)
```

## 関連項目

* 列挙体 [TimeSpanStyles](../../../system.globalization/timespanstyles/)
* 型エイリアス [ArrayPtr](../../arrayptr/)
* 型エイリアス [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [TimeSpan](../)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)