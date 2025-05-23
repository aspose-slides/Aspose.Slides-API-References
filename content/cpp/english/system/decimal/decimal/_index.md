---
title: Decimal()
second_title: Aspose.Slides for C++ API Reference
description: Constructs an instance that represents 0.
type: docs
weight: 1
url: /system/decimal/decimal/
---
## Decimal::Decimal() constructor


Constructs an instance that represents 0.

```cpp
System::Decimal::Decimal()
```

## Decimal::Decimal(std::int8_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::int8_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int8_t | 8-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::int16_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::int16_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int16_t | 16-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::int32_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::int32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int32_t | 32-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::int64_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::int64_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::int64_t | 64-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::uint8_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::uint8_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint8_t | unsigned 8-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::uint16_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::uint16_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint16_t | unsigned 16-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::uint32_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::uint32_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint32_t | unsigned 32-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(std::uint64_t) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(std::uint64_t i)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | std::uint64_t | unsigned 64-bit integer value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(float) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(float f)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| f | **float** | The single-precision floating-point value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(double) constructor


Constructs an instance that represents the specified value.

```cpp
System::Decimal::Decimal(double d)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | **double** | The double-precision floating-point value to be represented by the [Decimal](../) object being constructed |

## Decimal::Decimal(const std::string\&) constructor


Constructs an instance that represents a value whose string representation is specified as an instance of std::string class.

```cpp
System::Decimal::Decimal(const std::string &str)
```

## Decimal::Decimal(int32_t, int32_t, int32_t, bool, uint8_t) constructor


Constructs a [Decimal](../) object from the specified from the specified components.

```cpp
System::Decimal::Decimal(int32_t lo, int32_t mid, int32_t hi, bool isNegative, uint8_t scale)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lo | **int32_t** | The low 32 bits of the value |
| mid | **int32_t** | The middle 32 bits of the value |
| hi | **int32_t** | The high 32 bits of the value |
| isNegative | **bool** | Specifies if the value is negative |
| scale | **uint8_t** | A power of 10 ranging from 0 to 28 |

## Decimal::Decimal(const Decimal\&) constructor


Constructs an instance of [Decimal](../) class that represents the same number as the specified [Decimal](../) object.

```cpp
System::Decimal::Decimal(const Decimal &d)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | const [Decimal](../)\& | A [Decimal](../) object to copy the value from |

## Decimal::Decimal(const ArrayPtr\<int32_t\>\&) constructor


Constructs an instance of [Decimal](../) class from integer array containing a binary representation.

```cpp
System::Decimal::Decimal(const ArrayPtr<int32_t> &bits)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| bits | const [ArrayPtr](../../arrayptr/)\<**int32_t**\>\& | A integer array containing a binary representation. |

## Decimal::Decimal(std::nullptr_t) constructor


Always throws ArgumentNullException.

```cpp
System::Decimal::Decimal(std::nullptr_t bits)
```

## Decimal::Decimal(const number_type\&) constructor


Constructs an instance of [Decimal](../) class representing the specified value.

```cpp
System::Decimal::Decimal(const number_type &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [number_type](../number_type/)\& | A constant reference to the value to be represented by the object being constructed |

## See Also

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [number_type](../number_type/)
* Class [Decimal](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)