---
title: Sign()
second_title: Aspose.Slides for C++ API Reference
description: Determines the sign of the specified signed integral value.
type: docs
weight: 274
url: /system/math/sign/
---
## Math::Sign(T) method


Determines the sign of the specified signed integral value.

```cpp
template<typename T> static std::enable_if<std::is_integral<T>::value &&!std::is_unsigned<T>::value, int>::type System::Math::Sign(T value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The integral signed type |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### Return Value

-1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## Math::Sign(T) method


Determines the sign of the specified floating-point value.

```cpp
template<typename T> static std::enable_if<std::is_floating_point<T>::value, int>::type System::Math::Sign(T value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The floating point type of the argument |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T | The value to determine the sign of |

### Return Value

-1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## Math::Sign(const Decimal\&) method


Determines the sign of the specified decimal value.

```cpp
static int System::Math::Sign(const Decimal &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | The value to determine the sign of |

### Return Value

-1 if **value** is less than 0; 0 if **value** is equal to 0; 1 if **value** is greater than 0

## See Also

* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)