---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のカルチャで定義された書式規則を使用して、現在のオブジェクトが表す日付と時刻の値を文字列に変換して返します。
type: docs
weight: 482
url: /ja/system/datetime/tostring/
---
## DateTime::ToString() const メソッド

現在のオブジェクトが表す日付と時刻の値を、現在のカルチャで定義された書式規則を使用して文字列に変換して返します。

```cpp
String System::DateTime::ToString() const
```

### 戻り値

現在のオブジェクトが表す値の文字列表現

## DateTime::ToString(const String\&) const メソッド

現在のオブジェクトが表す日付と時刻の値を、指定された書式と現在のカルチャで定義された書式規則を使用して文字列に変換して返します。

```cpp
String System::DateTime::ToString(const String &format) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 書式文字列 |

### 戻り値

**format** と現在のカルチャで定義された書式に従ってフォーマットされた、現在のオブジェクトが表す値の文字列表現

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const メソッド

現在のオブジェクトが表す日付と時刻の値を、指定された書式情報を使用して文字列に変換して返します。

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 書式情報を表すオブジェクト |

### 戻り値

**formatProvider** が提供する書式情報に従ってフォーマットされた、現在のオブジェクトが表す値の文字列表現

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const メソッド




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const メソッド




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const メソッド

現在のオブジェクトが表す日付と時刻の値を、指定された書式情報を使用して文字列に変換して返します。

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| format | const [String](../../string/)\& | 書式文字列 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 書式情報を表すオブジェクト |

### 戻り値

**provider** が提供する書式情報と書式文字列 **format** に従ってフォーマットされた、現在のオブジェクトが表す値の文字列表現

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const メソッド




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const メソッド




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## 参照

* 型定義 [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [DateTime](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)