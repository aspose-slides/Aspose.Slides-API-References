---
title: operator+()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new instance of Decimal class that represents a value that is a sum of the specified value and the value represented by the specified Decimal object.
type: docs
weight: 2016
url: /cpp/system/operator_plus/
---
## System::operator+(const T\&, const [Decimal](../decimal/)\&) function


Returns a new instance of [Decimal](../decimal/) class that represents a value that is a sum of the specified value and the value represented by the specified [Decimal](../decimal/) object.

```cpp
template<typename T,typename _> Decimal System::operator+(const T &x, const Decimal &d)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const T\& | The first summand |
| d | const [Decimal](../decimal/)\& | The constant reference to the [Decimal](../decimal/) object representing the second summand |

### Return Value

A new instance of [Decimal](../decimal/) class that represents a value that is a sum of **x** and the value represented by the **d**.

## See Also

* Class [Decimal](../decimal/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator+(const T1\&, const [Nullable](../nullable/)\<T2\>\&) function


Sums non-nullable and nullable values.

```cpp
template<typename T1,typename T2,typename> auto System::operator+(const T1 &some, const Nullable<T2> &other) -> System::Nullable<decltype(some+other.get_Value())>
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Left operand type. |
| T2 | Right operand type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | Left operand. |
| other | const [Nullable](../nullable/)\<T2\>\& | Right operand. |

### Return Value

Summing result.

## See Also

* Class [Nullable](../nullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator+(T\&, const [String](../string/)\&) function


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringLiteral<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [String](../string/) literal type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | Literal to concatenate to string. |
| right | const [String](../string/)\& | [String](../string/) to concatenate. |

### Return Value

Concatenated string.

## See Also

* Struct [IsStringLiteral](../isstringliteral/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator+(T\&, const [String](../string/)\&) function


[String](../string/) concatenation.

```cpp
template<typename T> std::enable_if<IsStringPointer<T, char_t>::value, String>::type System::operator+(T &left, const String &right)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [String](../string/) pointer type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer to concatenate to string. |
| right | const [String](../string/)\& | [String](../string/) to concatenate. |

### Return Value

Concatenated string.

## See Also

* Struct [IsStringPointer](../isstringpointer/)
* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::operator+(const char_t, const [String](../string/)\&) function


[String](../string/) concatenation.

```cpp
String System::operator+(const char_t left, const String &right)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const char_t | Character to concatenate to string. |
| right | const [String](../string/)\& | [String](../string/) to concatenate. |

### Return Value

Concatenated string.

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
