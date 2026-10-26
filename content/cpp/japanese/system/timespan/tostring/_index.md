---
title: ToString()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表す時間間隔の文字列表現を返します。
type: docs
weight: 261
url: /ja/system/timespan/tostring/
---
## TimeSpan::ToString() const メソッド


現在のオブジェクトが表す時間間隔の文字列表現を返します。

```cpp
String System::TimeSpan::ToString() const
```

## TimeSpan::ToString(const String\&) const メソッド


指定されたフォーマットを使用して、現在のオブジェクトの値を同等の文字列表現に変換します。

```cpp
String System::TimeSpan::ToString(const String &format) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const メソッド


指定されたフォーマットおよびフォーマットプロバイダーを使用して、現在のオブジェクトの値を同等の文字列表現に変換します。

```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const メソッド




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## TimeSpan::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const メソッド




```cpp
String System::TimeSpan::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## TimeSpan::ToString(const String\&, std::nullptr_t) const メソッド




```cpp
String System::TimeSpan::ToString(const String &format, std::nullptr_t) const
```

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* クラス [String](../../string/)
* クラス [TimeSpan](../)
* クラス [IFormatProvider](../../iformatprovider/)
* クラス [CultureInfo](../../../system.globalization/cultureinfo/)
* クラス [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)