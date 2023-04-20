---
title: ToDouble()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified boolean value to an equivalent double-precision floating-point number.
type: docs
weight: 222
url: /cpp/system/convert/todouble/
---
## Convert::ToDouble(bool) method


Converts the specified boolean value to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(bool value)
```

## Convert::ToDouble(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(uint8_t value)
```

## Convert::ToDouble(int8_t) method


Converts the specified 8-bit signed integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(int8_t value)
```

## Convert::ToDouble(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(uint16_t value)
```

## Convert::ToDouble(int16_t) method


Converts the specified 16-bit signed integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(int16_t value)
```

## Convert::ToDouble(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(uint32_t value)
```

## Convert::ToDouble(int32_t) method


Converts the specified 32-bit signed integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(int32_t value)
```

## Convert::ToDouble(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(uint64_t value)
```

## Convert::ToDouble(int64_t) method


Converts the specified 64-bit signed integer to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(int64_t value)
```

## Convert::ToDouble(float) method


Converts the specified single-precision number to an equivalent double-precision floating-point number.

```cpp
static constexpr double System::Convert::ToDouble(float value)
```

## Convert::ToDouble(double) method


Returns the specified double number.

```cpp
static constexpr double System::Convert::ToDouble(double value)
```

## Convert::ToDouble(const Decimal\&) method


Converts the specified decimal number to an equivalent double-precision floating-point number.

```cpp
static double System::Convert::ToDouble(const Decimal &value)
```

## Convert::ToDouble(char_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static double System::Convert::ToDouble(char_t value)
```

## Convert::ToDouble(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static double System::Convert::ToDouble(DateTime value)
```

## Convert::ToDouble(std::nullptr_t) method


Converts the specified null-string to the equivalent double-precision floating-point value.

```cpp
static constexpr double System::Convert::ToDouble(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToDouble(const char_t *) method


Converts the specified c-string containing the string representation of a number to the equivalent double-precision floating-point value.

```cpp
static double System::Convert::ToDouble(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

The double-precision floating-point value equal to the number represented by the specified c-string

## Convert::ToDouble(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value.

```cpp
static double System::Convert::ToDouble(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string

## Convert::ToDouble(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information.

```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, std::nullptr_t) method




```cpp
static double System::Convert::ToDouble(const String &value, std::nullptr_t)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent double-precision floating-point value using the provided formatting information and number style.

```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The double-precision floating-point value equal to the number represented by the specified string

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToDouble(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static double System::Convert::ToDouble(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToDouble(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to double-precision floating-point value. If the type of boxed value is [String](../../string/), the specified string format is used during conversion.

```cpp
static double System::Convert::ToDouble(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

A double-precision floating-point value equivalent to the specified boxed value

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