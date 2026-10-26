---
title: Parse()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列を同等の TimeSpan オブジェクトに変換します。
type: docs
weight: 534
url: /ja/system/timespan/parse/
---
## TimeSpan::Parse(const String\&) メソッド

文字列を同等の [TimeSpan](../) オブジェクトに変換します。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |

### 戻り値

文字列に対応する時間間隔。

## TimeSpan::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) メソッド

指定された書式プロバイダーを使用して、文字列を同等の [TimeSpan](../) オブジェクトに変換します。

```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<IFormatProvider> &provider)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文化固有の書式情報を提供する書式プロバイダー。 |

### 戻り値

文字列に対応する時間間隔。

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) メソッド




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture)
```

## TimeSpan::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) メソッド




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## TimeSpan::Parse(const String\&, std::nullptr_t) メソッド




```cpp
static TimeSpan System::TimeSpan::Parse(const String &input, std::nullptr_t)
```

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [TimeSpan](../)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)