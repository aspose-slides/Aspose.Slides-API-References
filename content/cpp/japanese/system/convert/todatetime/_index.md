---
title: ToDateTime()
second_title: Aspose.Slides for C++ API リファレンス
description: 変換はサポートされていません。常に InvalidCastException がスローされます。
type: docs
weight: 248
url: /ja/system/convert/todatetime/
---
## Convert::ToDateTime(bool) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) メソッド

変換はサポートされていません。常に InvalidCastException をスローします。

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) メソッド

指定された日時を返します。

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) メソッド

指定された文字列を [DateTime](../../datetime/) クラスのインスタンスに変換します。

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |

### 戻り値

指定された文字列が表す日時情報を表す [DateTime](../../datetime/) クラスのインスタンス

## Convert::ToDateTime(const String\&, const SharedPtr<IFormatProvider>\&) メソッド

提供された書式情報を使用して、指定された文字列を [DateTime](../../datetime/) クラスのインスタンスに変換します。

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 変換する文字列 |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 文字列書式情報を含むオブジェクトへのポインタ |

### 戻り値

指定された文字列が表す日時情報を表す [DateTime](../../datetime/) クラスのインスタンス

## Convert::ToDateTime(const String\&, const SharedPtr<Globalization::CultureInfo>\&) メソッド




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr<Globalization::DateTimeFormatInfo>\&) メソッド




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) メソッド




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr<Object>\&, const SharedPtr<IFormatProvider>\&) メソッド

指定されたボックス化された値を同等の [DateTime](../../datetime/) 値に変換します。

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 変換する値をボックス化しているオブジェクトへの共有ポインタ |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | ボックス化された値の型が [String](../../string/) の場合に使用する文字列書式 |

### 戻り値

指定されたボックス化された値と同等の [DateTime](../../datetime/) 値

## 参照

* Typedef [SharedPtr](../../sharedptr/)
* Class [DateTime](../../datetime/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)