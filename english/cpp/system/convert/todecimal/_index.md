---
title: ToDecimal()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified boolean value to an equivalent decimal number.
type: docs
weight: 235
url: /cpp/system/convert/todecimal/
---
## Convert::ToDecimal(bool) method


Converts the specified boolean value to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(bool value)
```

## Convert::ToDecimal(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(uint8_t value)
```

## Convert::ToDecimal(int8_t) method


Converts the specified 8-bit signed integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(int8_t value)
```

## Convert::ToDecimal(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(uint16_t value)
```

## Convert::ToDecimal(int16_t) method


Converts the specified 16-bit signed integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(int16_t value)
```

## Convert::ToDecimal(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(uint32_t value)
```

## Convert::ToDecimal(int32_t) method


Converts the specified 32-bit signed integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(int32_t value)
```

## Convert::ToDecimal(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(uint64_t value)
```

## Convert::ToDecimal(int64_t) method


Converts the specified 64-bit signed integer to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(int64_t value)
```

## Convert::ToDecimal(float) method


Converts the specified float number to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(float value)
```

## Convert::ToDecimal(double) method


Converts the specified double number to an equivalent decimal number.

```cpp
static Decimal System::Convert::ToDecimal(double value)
```

## Convert::ToDecimal(const Decimal\&) method


Returns the specified decimal number.

```cpp
static Decimal System::Convert::ToDecimal(const Decimal &value)
```

## Convert::ToDecimal(char_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(char_t value)
```

## Convert::ToDecimal(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static Decimal System::Convert::ToDecimal(DateTime value)
```

## Convert::ToDecimal(std::nullptr_t) method


Converts the specified null-string to the equivalent [Decimal](../../decimal/) value.

```cpp
static Decimal System::Convert::ToDecimal(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToDecimal(const char_t *) method


Converts the specified c-string containing the string representation of a number to the equivalent [Decimal](../../decimal/) value.

```cpp
static Decimal System::Convert::ToDecimal(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

The [Decimal](../../decimal/) value equal to the number represented by the specified c-string

## Convert::ToDecimal(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../../decimal/) value.

```cpp
static Decimal System::Convert::ToDecimal(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

The [Decimal](../../decimal/) value equal to the number represented by the specified string

## Convert::ToDecimal(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../../decimal/) value using the provided formatting information.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The [Decimal](../../decimal/) value equal to the number represented by the specified string

## Convert::ToDecimal(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent [Decimal](../../decimal/) value using the specified number styles and formatting information.

```cpp
static Decimal System::Convert::ToDecimal(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The [Decimal](../../decimal/) value equal to the number represented by the specified string

## Convert::ToDecimal(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent [Decimal](../../decimal/) value.

```cpp
static Decimal System::Convert::ToDecimal(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

A [Decimal](../../decimal/) value equivalent to the specified boxed value

## See Also

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)