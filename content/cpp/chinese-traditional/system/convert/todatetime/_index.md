---
title: ToDateTime()
second_title: Aspose.Slides for C++ API 參考
description: 不支援轉換。始終拋出 InvalidCastException.
type: docs
weight: 248
url: /zh-hant/system/convert/todatetime/
---
## Convert::ToDateTime(bool) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) 方法

Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) 方法

Returns the specified date and time.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) 方法

Converts the specified string to an instance of [DateTime](../../datetime/) class.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |

### 傳回值

An instance of [DateTime](../../datetime/) class representing the date and time information represented by the specified string

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) 方法

Converts the specified string to an instance of [DateTime](../../datetime/) class using the provided formatting information.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串 |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊的物件的指標 |

### 傳回值

An instance of [DateTime](../../datetime/) class representing the date and time information represented by the specified string

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) 方法




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) 方法

Converts the specified boxed value to equivalent [DateTime](../../datetime/) value.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 封裝要轉換之值的物件的 shared pointer |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 如果封裝值的類型為 [String](../../string/)，則使用的字串格式 |

### 傳回值

A [DateTime](../../datetime/) value equivalent to the specified boxed value

## 另請參閱

* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [DateTime](../../datetime/)
* 類別 [Decimal](../../decimal/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 類別 [Object](../../object/)
* 結構 [Convert](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)