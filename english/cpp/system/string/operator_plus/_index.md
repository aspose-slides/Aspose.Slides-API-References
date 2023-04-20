---
title: operator+()
second_title: Aspose.Slides for C++ API Reference
description: String concatenation operator.
type: docs
weight: 261
url: /cpp/system/string/operator_plus/
---
## String::operator+(const String\&) const method


[String](../) concatenation operator.

```cpp
String System::String::operator+(const String &str) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) to add to the end of current one. |

### Return Value

Concatenated string.

## String::operator+(const T\&) const method


[String](../) concatenation with string literal or character string pointer.

```cpp
template<typename T,std::enable_if_t< IsStringLiteral< T, char_t >::value > *> String System::String::operator+(const T &arg) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | One of string literal or character string pointer forms. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | const T\& | Entity to concatenate with current string. |

### Return Value

Concatenated string.

## String::operator+(char_t) const method


Adds character to the end of the string.

```cpp
String System::String::operator+(char_t x) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | char_t | Character to add. |

### Return Value

[String](../) concatenation result.

## String::operator+(int) const method


Adds integer value string representation to the end of the string.

```cpp
String System::String::operator+(int i) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | int | Integer value to convert to string and to add. |

### Return Value

[String](../) concatenation result.

## String::operator+(uint32_t) const method


Adds unsigned integer value string representation to the end of the string.

```cpp
String System::String::operator+(uint32_t i) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| i | **uint32_t** | Value to convert to string and to add. |

### Return Value

[String](../) concatenation result.

## String::operator+(double) const method


Adds floating point value string representation to the end of the string.

```cpp
String System::String::operator+(double d) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| d | **double** | Value to convert to string and to add. |

### Return Value

[String](../) concatenation result.

## String::operator+(int64_t) const method


Adds integer value string representation to the end of the string.

```cpp
String System::String::operator+(int64_t v) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| v | **int64_t** | Value to convert to string and to add to add. |

### Return Value

[String](../) concatenation result.

## String::operator+(const T\&) const method


Adds reference type object string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t< IsSmartPtr< T >::value > *> String System::String::operator+(const T &value) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | pointer type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) to convert to string using [ToString()](../tostring/) call and to add to current string. |

### Return Value

[String](../) concatenation result.

## String::operator+(const T\&) const method


Adds value type object string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t<!IsSmartPtr< T >::value &&!std::is_scalar< T >::value &&!std::is_array< T >::value > *> String System::String::operator+(const T &value) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type to call [ToString()](../tostring/) upon. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Object](../../object/) to convert to string using [ToString()](../tostring/) call and to add to current string. |

### Return Value

[String](../) concatenation result.

## String::operator+(T) const method


Adds boolean value string representation to the end of the string.

```cpp
template<typename T,std::enable_if_t< std::is_same< T, bool >::value > *> String System::String::operator+(T arg) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type to concatenate with string. Must be bool |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | [Boolean](../../boolean/) value to convert to string and to add. |

### Return Value

[String](../) concatenation result.

## See Also

* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)