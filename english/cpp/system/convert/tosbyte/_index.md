---
title: ToSByte()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified boolean value to an equivalent 8-bit signed integer.
type: docs
weight: 105
url: /cpp/system/convert/tosbyte/
---
## Convert::ToSByte(bool) method


Converts the specified boolean value to an equivalent 8-bit signed integer.

```cpp
static constexpr int8_t System::Convert::ToSByte(bool value)
```

## Convert::ToSByte(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint8_t value)
```

## Convert::ToSByte(int8_t) method


Returns the specified 8-bit signed integer.

```cpp
static constexpr int8_t System::Convert::ToSByte(int8_t value)
```

## Convert::ToSByte(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint16_t value)
```

## Convert::ToSByte(int16_t) method


Converts the specified 16-bit signed integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(int16_t value)
```

## Convert::ToSByte(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint32_t value)
```

## Convert::ToSByte(int32_t) method


Converts the specified 32-bit signed integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(int32_t value)
```

## Convert::ToSByte(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(uint64_t value)
```

## Convert::ToSByte(int64_t) method


Converts the specified 64-bit signed integer to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(int64_t value)
```

## Convert::ToSByte(float) method


Converts the specified float number to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(float value)
```

## Convert::ToSByte(double) method


Converts the specified double number to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(double value)
```

## Convert::ToSByte(const Decimal\&) method


Converts the specified decimal number to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(const Decimal &value)
```

## Convert::ToSByte(char_t) method


Converts the specified unicode character to an equivalent 8-bit signed integer.

```cpp
static int8_t System::Convert::ToSByte(char_t value)
```

## Convert::ToSByte(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static int8_t System::Convert::ToSByte(DateTime value)
```

## Convert::ToSByte(std::nullptr_t) method


Converts the specified null-string to the equivalent 8-bit integer value.

```cpp
static constexpr int8_t System::Convert::ToSByte(std::nullptr_t)
```


### Return Value

Zero.

## Convert::ToSByte(const char_t *) method


Converts the specified c-string containing the string representation of a number to the equivalent 8-bit integer value.

```cpp
static int8_t System::Convert::ToSByte(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

The 8-bit integer value equal to the number represented by the specified c-string

## Convert::ToSByte(const String\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit integer value.

```cpp
static int8_t System::Convert::ToSByte(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

The 8-bit integer value equal to the number represented by the specified string

## Convert::ToSByte(const String\&, int) method


Converts the specified string containing the string representation of a number in the specified base to the equivalent 8-bit integer value.

```cpp
static int8_t System::Convert::ToSByte(const String &value, int from_base)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| from_base | int | The base of the number represented by the string |

### Return Value

The 8-bit integer value equal to the number represented by the specified string

## Convert::ToSByte(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent unsigned 8-bit integer value using the provided formatting information.

```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The 8-bit integer value equal to the number represented by the specified string

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, std::nullptr_t) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, std::nullptr_t)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string containing the string representation of a number to the equivalent 8-bit integer value using the provided formatting information and number style.

```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | A bitwise combination of values of NumberStyles enum that specifies the permitted style of the string representation of a number |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A pointer to an object that contains the string format information |

### Return Value

The unsigned 8-bit integer value equal to the number represented by the specified string

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Convert::ToSByte(const String\&, Globalization::NumberStyles, std::nullptr_t) method




```cpp
static int8_t System::Convert::ToSByte(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Convert::ToSByte(Enum) method




```cpp
template<typename Enum,typename> static int8_t System::Convert::ToSByte(Enum value)
```

## Convert::ToSByte(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent 8-bit integer value.

```cpp
static int8_t System::Convert::ToSByte(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

An 8-bit integer value equivalent to the specified boxed value

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