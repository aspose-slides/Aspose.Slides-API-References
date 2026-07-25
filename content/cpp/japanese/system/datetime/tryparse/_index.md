---
title: TryParse()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された日付と時刻の文字列表現を同等の DateTime オブジェクトに変換します。
type: docs
weight: 885
url: /ja/system/datetime/tryparse/
---
## DateTime::TryParse(const String\&, DateTime\&) メソッド

指定された日付と時刻の文字列表現を同等の [DateTime](../) オブジェクトに変換します。

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象となる日付と時刻の文字列表現。 |
| result | [DateTime](../)\& | 変換が成功した場合、変換結果を格納する出力引数。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## DateTime::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) メソッド

指定された文化固有の書式情報とスタイルを使用して、指定された日付と時刻の文字列表現を同等の [DateTime](../) オブジェクトに変換します。

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 変換対象となる日付と時刻の文字列表現。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文化固有の書式情報を提供する [IFormatProvider](../../iformatprovider/) オブジェクト。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列挙値のビット単位の組み合わせで、**s** に関する追加情報、**s** に存在し得るスタイル要素、または **s** から [DateTime](../) オブジェクトへの変換に関する情報を提供します。 |
| result | [DateTime](../)\& | 変換が成功した場合、変換結果を格納する出力引数。 |

### 戻り値

変換が成功した場合は true、そうでない場合は false。

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) メソッド

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) メソッド

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) メソッド

```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 参照

* 列挙体 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [DateTime](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)