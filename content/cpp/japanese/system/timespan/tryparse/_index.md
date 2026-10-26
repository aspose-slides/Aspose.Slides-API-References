---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 文字列を同等の TimeSpan オブジェクトに変換し、変換結果を返します。
type: docs
weight: 560
url: /ja/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) メソッド

文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列が正常に変換された場合は true、それ以外の場合は false。

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) メソッド

指定されたフォーマットプロバイダーを使用して文字列を同等の [TimeSpan](../) オブジェクトに変換し、変換結果を返します。

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | 入力文字列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文化特有の書式設定情報を提供するフォーマットプロバイダー。 |
| result | [TimeSpan](../)\& | 文字列に対応する時間間隔。 |

### 戻り値

文字列が正常に変換された場合は true、それ以外の場合は false。

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) メソッド




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) メソッド




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TrySort(const String\&, std::nullptr_t, TimeSpan\&) メソッド




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## 関連項目

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [TimeSpan](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 名前空間 [System](../../)
* Library [Aspose.Slides](../../../)