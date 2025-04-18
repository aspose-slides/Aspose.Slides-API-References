---
title: ToChar()
second_title: Aspose.Slides for C++ API Reference
description: Conversion is not supported. Always throws InvalidCastException.
type: docs
weight: 118
url: /system/convert/tochar/
---
## Convert::ToChar(bool) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent unicode character.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) method


Converts the specified 8-bit signed integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent unicode character.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) method


Converts the specified 16-bit signed integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) method


Converts the specified 32-bit signed integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) method


Converts the specified 64-bit signed integer to an equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) method


Returns the specified unicode character.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) method


Converts the first and the only character of the specified c-string to a char_t value.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert; it is expected that the c-string be exactly 1 character long. |

### Return Value

The first and the only character of the specified c-string if it is exactly 1 characetr long, otherwise - 0

## Convert::ToChar(const String\&) method


Converts the first and the only character of the specified string to a char_t value.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert; it is expected that the string be exactly 1 character long |

### Return Value

The first and the only character of the specified string if it is exactly 1 characetr long, otherwise - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the first and the only character of the specified string to a char_t value.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert; it is expected that the string be exactly 1 character long |

### Return Value

The first and the only character of the specified string if it is exactly 1 characetr long, otherwise - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent unicode character.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

An unicode character equivalent to the specified boxed value

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Decimal](../../decimal/)
* Class [DateTime](../../datetime/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [Object](../../object/)
* Struct [Convert](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)