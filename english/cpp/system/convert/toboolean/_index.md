---
title: ToBoolean()
second_title: Aspose.Slides for C++ API Reference
description: Returns the specified boolean value.
type: docs
weight: 79
url: /cpp/system/convert/toboolean/
---
## Convert::ToBoolean(bool) method


Returns the specified boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) method


Converts the specified 8-bit unsigned integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) method


Converts the specified 8-bit signed integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) method


Converts the specified 16-bit unsigned integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) method


Converts the specified 16-bit signed integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) method


Converts the specified 32-bit unsigned integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) method


Converts the specified 32-bit signed integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) method


Converts the specified 64-bit unsigned integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) method


Converts the specified 64-bit signed integer to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) method


Converts the specified float number to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) method


Converts the specified double number to an equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) method


Converts the specified decimal number to an equivalent boolean value.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) method


Conversion is not supported. Always throws InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) method


Converts the specified null-string to the equivalent boolean value.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Return Value

False.

## Convert::ToBoolean(const char_t *) method


Converts the specified c-string to the value of bool type.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | The c-string to convert |

### Return Value

True if the specified c-string is equal to \"True\" and false if the specified c-string is equal to \"False\".

## Convert::ToBoolean(const String\&) method


Converts the specified string to the value of bool type.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

True if the specified c-string is equal to \"True\" and false if the specified string is equal to \"False\".

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified string to the value of bool type.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string to convert |

### Return Value

True if the specified c-string is equal to \"True\" and false if the specified string is equal to \"False\".

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) method


Converts the specified boxed value to equivalent boolean value.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The shared pointer to the object boxing the value to convert |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | The string format to be used if the type of the boxed value is [String](../../string/) |

### Return Value

An boolean value equivalent to the specified boxed value

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