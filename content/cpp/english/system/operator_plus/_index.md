---
title: operator+()
second_title: Aspose.Slides for C++ API Reference
description: Returns a new instance of Decimal class that represents a value that is a sum of the specified value and the value represented by the specified Decimal object.
type: docs
weight: 2055
url: /system/operator_plus/
---
## System::operator+(const T\&, const Decimal\&) function


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

## System::operator+(MulticastDelegate\<T\>, MulticastDelegate\<T\>) function


Connects all callbacks from right hand delegate to the end of left hand delegate callback list.

```cpp
template<typename T> MulticastDelegate<T> System::operator+(MulticastDelegate<T> lhv, MulticastDelegate<T> rhv)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| lhv | MulticastDelegate\<T\> | The delegate to which callbacks are added. |
| rhv | MulticastDelegate\<T\> | The delegate whose callbacks are being added. |

### Return Value

Returns a delegate that contains the callbacks of the left hand value and then the right hand ones.

## System::operator+(const T1\&, const Nullable\<T2\>\&) function


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

## System::operator+(T\&, const String\&) function


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

## System::operator+(T\&, const String\&) function


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

## System::operator+(const char_t, const String\&) function


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

* Class [Decimal](../decimal/)
* Class [Nullable](../nullable/)
* Class [String](../string/)
* Struct [IsStringLiteral](../isstringliteral/)
* Struct [IsStringPointer](../isstringpointer/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)