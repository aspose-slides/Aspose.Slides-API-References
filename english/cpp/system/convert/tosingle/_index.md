---
title: ToSingle()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified boolean value to an equivalent single-precision floating-point number.
type: docs
weight: 209
url: /cpp/system/convert/tosingle/
---
## Convert::ToSingle(bool) method


Converts the specified boolean value to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(bool value)
```

## Convert::ToSingle(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(uint8_t value)
```

## Convert::ToSingle(int8_t) method


Converts the specified 8-bit signed integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(int8_t value)
```

## Convert::ToSingle(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(uint16_t value)
```

## Convert::ToSingle(int16_t) method


Converts the specified 16-bit signed integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(int16_t value)
```

## Convert::ToSingle(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(uint32_t value)
```

## Convert::ToSingle(int32_t) method


Converts the specified 32-bit signed integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(int32_t value)
```

## Convert::ToSingle(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(uint64_t value)
```

## Convert::ToSingle(int64_t) method


Converts the specified 64-bit signed integer to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(int64_t value)
```

## Convert::ToSingle(float) method


Returns the specified float number.

```cpp
static constexpr float System::Convert::ToSingle(float value)
```

## Convert::ToSingle(double) method


Converts the specified double-precision number to an equivalent single-precision floating-point number.

```cpp
static constexpr float System::Convert::ToSingle(double value)
```

## Convert::ToSingle(const Decimal\&) method


Converts the specified decimal number to an equivalent single-precision floating-point number.

```cpp
static float System::Convert::ToSingle(const Decimal &value)
```

## Convert::ToSingle(char_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static float System::Convert::ToSingle(char_t value)
```

## Convert::ToSingle(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static float System::Convert::ToSingle(DateTime value)
```

## Convert::ToSingle(std::nullptr_t) method


Converts the specified null-string to the equivalent single-precision floating-point value.

```cpp
static constexpr float System::Convert::ToSingle(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToSingle(const char_t *) method


Converts the specified c-string containing the string representation of a number to the equivalent single-precision floating-point value.

```cpp
static float System::Convert::ToSingle(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

The single-precision floating-point value equal to the number represented by the specified c-string

## Convert::ToSingle(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value.

```cpp
static float System::Convert::ToSingle(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string

## Convert::ToSingle(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information.

```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static float System::Convert::ToSingle(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, std::nullptr_t) method




```cpp
static float System::Convert::ToSingle(const String &value, std::nullptr_t)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent single-precision floating-point value using the provided formatting information and number style.

```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The single-precision floating-point value equal to the number represented by the specified string

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSingle(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static float System::Convert::ToSingle(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSingle(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to single-precision floating-point value.

```cpp
static float System::Convert::ToSingle(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

A single-precision floating-point value equivalent to the specified boxed value

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)