---
title: ToUInt16()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified boolean value to an equivalent 16-bit unsigned integer.
type: docs
weight: 144
url: /system/convert/touint16/
---
## Convert::ToUInt16(bool) method


Converts the specified boolean value to an equivalent 16-bit unsigned integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(bool value)
```

## Convert::ToUInt16(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent 16-bit unsigned integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint8_t value)
```

## Convert::ToUInt16(int8_t) method


Converts the specified 8-bit signed integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(int8_t value)
```

## Convert::ToUInt16(uint16_t) method


Returns the specified 16-bit unsigned integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(uint16_t value)
```

## Convert::ToUInt16(int16_t) method


Converts the specified 16-bit signed integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(int16_t value)
```

## Convert::ToUInt16(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint32_t value)
```

## Convert::ToUInt16(int32_t) method


Converts the specified 32-bit signed integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(int32_t value)
```

## Convert::ToUInt16(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(uint64_t value)
```

## Convert::ToUInt16(int64_t) method


Converts the specified 64-bit signed integer to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(int64_t value)
```

## Convert::ToUInt16(float) method


Converts the specified float number to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(float value)
```

## Convert::ToUInt16(double) method


Converts the specified double number to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(double value)
```

## Convert::ToUInt16(const Decimal\&) method


Converts the specified decimal number to an equivalent 16-bit unsigned integer.

```cpp
static uint16_t System::Convert::ToUInt16(const Decimal &value)
```

## Convert::ToUInt16(char_t) method


Converts the specified unicode character to an equivalent 16-bit unsigned integer.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(char_t value)
```

## Convert::ToUInt16(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static uint16_t System::Convert::ToUInt16(DateTime value)
```

## Convert::ToUInt16(std::nullptr_t) method


Converts the specified null-string to the equivalent unsigned 16-bit integer value.

```cpp
static constexpr uint16_t System::Convert::ToUInt16(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToUInt16(const char_t *) method


Converts the specified c-string containing the string representation of a number to the equivalent unsigned 16-bit integer value.

```cpp
static uint16_t System::Convert::ToUInt16(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

The unsigned 16-bit integer value equal to the number represented by the specified c-string

## Convert::ToUInt16(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

The unsigned 16-bit integer value equal to the number represented by the specified string

## Convert::ToUInt16(const String\&, int) method


Converts the specified string containing the string representation of a number in the specified base to the equivalent unsigned 16-bit integer value.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, int from_base)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| from_base | int | The base of the number represented by the string |

### Return Value

The unsigned 16-bit integer value equal to the number represented by the specified string

## Convert::ToUInt16(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value using the provided formatting information.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The unsigned 16-bit integer value equal to the number represented by the specified string

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, std::nullptr_t) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, std::nullptr_t)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent unsigned 16-bit integer value using the provided formatting information and number style.

```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The unsigned 16-bit integer value equal to the number represented by the specified string

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToUInt16(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static uint16_t System::Convert::ToUInt16(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToUInt16(Enum) method




```cpp
template<typename Enum,typename> static uint16_t System::Convert::ToUInt16(Enum value)
```

## Convert::ToUInt16(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent unsigned 16-bit integer value.

```cpp
static uint16_t System::Convert::ToUInt16(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

An unsigned 16-bit integer value equivalent to the specified boxed value

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
* Struct [Enum](../../enum/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)