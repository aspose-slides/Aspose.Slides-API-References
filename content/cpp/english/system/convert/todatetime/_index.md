---
title: ToDateTime()
second_title: Aspose.Slides for C++ API Reference
description: Conversion is not supported. Always throws InvalidCastException.
type: docs
weight: 248
url: /system/convert/todatetime/
---
## Convert::ToDateTime(bool) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(bool value)
```

## Convert::ToDateTime(uint8_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint8_t value)
```

## Convert::ToDateTime(int8_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int8_t value)
```

## Convert::ToDateTime(uint16_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint16_t value)
```

## Convert::ToDateTime(int16_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int16_t value)
```

## Convert::ToDateTime(uint32_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint32_t value)
```

## Convert::ToDateTime(int32_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int32_t value)
```

## Convert::ToDateTime(uint64_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(uint64_t value)
```

## Convert::ToDateTime(int64_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(int64_t value)
```

## Convert::ToDateTime(float) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(float value)
```

## Convert::ToDateTime(double) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(double value)
```

## Convert::ToDateTime(const Decimal\&) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(const Decimal &value)
```

## Convert::ToDateTime(char_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static DateTime System::Convert::ToDateTime(char_t value)
```

## Convert::ToDateTime(DateTime) method


Returns the specified date and time.

```cpp
static constexpr DateTime System::Convert::ToDateTime(DateTime value)
```

## Convert::ToDateTime(const String\&) method


Converts the specified string to an instance of [DateTime](../../datetime/) class.

```cpp
static DateTime System::Convert::ToDateTime(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

An instance of [DateTime](../../datetime/) class representing the date and time information represented by the specified string

## Convert::ToDateTime(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string to an instance of [DateTime](../../datetime/) class using the provided formatting information.

```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<IFormatProvider> &fp)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

An instance of [DateTime](../../datetime/) class representing the date and time information represented by the specified string

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDateTime(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi)
```

## Convert::ToDateTime(const String\&, std::nullptr_t) method




```cpp
static DateTime System::Convert::ToDateTime(const String &value, std::nullptr_t)
```

## Convert::ToDateTime(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent [DateTime](../../datetime/) value.

```cpp
static DateTime System::Convert::ToDateTime(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

A [DateTime](../../datetime/) value equivalent to the specified boxed value

## See Also

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