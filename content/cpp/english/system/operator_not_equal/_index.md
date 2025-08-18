---
title: operator!=()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 1977
url: /system/operator_not_equal/
---
## System::operator!=(ArraySegment\<T\>, ArraySegment\<T\>) function




```cpp
template<typename T> bool System::operator!=(ArraySegment<T> a, ArraySegment<T> b)
```

## System::operator!=(std::nullptr_t, DateTime) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, DateTime)
```

## System::operator!=(std::nullptr_t, const DateTimeOffset\&) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, const DateTimeOffset &)
```

## System::operator!=(std::nullptr_t, const Nullable\<T\>\&) function


Determines if the specified [Nullable](../nullable/) object represents a value that is not equal to null.

```cpp
template<typename T> bool System::operator!=(std::nullptr_t, const Nullable<T> &other)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | std::nullptr_t | A constant reference to an [Nullable](../nullable/) object to test |

### Return Value

True if the specified object represents non-null value, false otherwise

## System::operator!=(const T1\&, const Nullable\<T2\>\&) function


Determines if the specified value is not equal to the value represented by the specified [Nullable](../nullable/) object by applying [operator!=()](./) to these values.

```cpp
template<typename T1,typename T2> std::enable_if<!IsNullable<T1>::value, bool>::type System::operator!=(const T1 &some, const Nullable<T2> &other)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | The type of the first comparand value |
| T2 | The underlying type of the [Nullable](../nullable/) object that represents the second comparand value |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| some | const T1\& | A constant reference to the value that is to be used as the first comparand |
| other | const [Nullable](../nullable/)\<T2\>\& | A constant reference to the [Nullable](../nullable/) object the represented value of which is to be used as the second comparand |

### Return Value

True if the comparands are not equal, otherwise - false

## System::operator!=(const SmartPtr\<X\>\&, const SmartPtr\<Y\>\&) function


Non-equal-compares two smart pointers.

```cpp
template<class X,class Y> bool System::operator!=(const SmartPtr<X> &x, const SmartPtr<Y> &y)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | Pointee type of first pointer. |
| Y | Pointee type of second pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | First pointer to compare. |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | Second pointer to compare. |

### Return Value

False if pointers match, true otherwise.

## System::operator!=(SmartPtr\<X\> const\&, std::nullptr_t) function


Checks if smart pointer is not null.

```cpp
template<class X> bool System::operator!=(SmartPtr<X> const &x, std::nullptr_t)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | Pointee type of pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | [SmartPtr](../smartptr/)\<X\> const\& | Pointer to check. |

### Return Value

False if pointer is null, true otherwise.

## System::operator!=(std::nullptr_t, SmartPtr\<X\> const\&) function


Checks if smart pointer is not null.

```cpp
template<class X> bool System::operator!=(std::nullptr_t, SmartPtr<X> const &x)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | Pointee type of pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | std::nullptr_t | Pointer to check. |

### Return Value

False if pointer is null, true otherwise.

## System::operator!=(const SmartPtr\<X\>\&, const Y *) function


Inequality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, Y>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const SmartPtr<X> &x, const Y *y)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | type of smart pointer. |
| Y | type of simple pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const [SmartPtr](../smartptr/)\<X\>\& | smart pointer to compare (left). |
| y | const Y * | pointer to compare (right). |

### Return Value

False if pointers match, true otherwise.

## System::operator!=(const X *, const SmartPtr\<Y\>\&) function


Equality comparison smart pointer against simple (C) pointer.

```cpp
template<class X,class Y> std::enable_if<std::is_base_of<Object, X>::value &&detail::has_no_operator_equal<X, Y>::value, bool>::type System::operator!=(const X *x, const SmartPtr<Y> &y)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| X | type of simple pointer. |
| Y | type of smart pointer. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| x | const X * | pointer to compare (right). |
| y | const [SmartPtr](../smartptr/)\<Y\>\& | smart pointer to compare (left). |

### Return Value

False if pointers match, true otherwise.

## System::operator!=(Chars\&, const String\&) function


[String](../string/) comparison.

```cpp
template<class Chars,typename std::enable_if< IsStringLiteral< Chars, char_t >::value >::type *> bool System::operator!=(Chars &left, const String &right)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Chars | [String](../string/) literal type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | Chars\& | [String](../string/) literal to compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Return Value

false if strings match, true otherwise.

## System::operator!=(T\&, const String\&) function


[String](../string/) comparison.

```cpp
template<class T,typename std::enable_if< IsStringPointer< T, char_t >::value >::type *> bool System::operator!=(T &left, const String &right)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [String](../string/) pointer type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | T\& | [String](../string/) pointer to compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Return Value

false if strings match, true otherwise.

## System::operator!=(const SharedPtr\<Object\>\&, const String\&) function


[Object](../object/) and string comparison.

```cpp
bool System::operator!=(const SharedPtr<Object> &left, const String &right)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| left | const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\& | [Object](../object/) to convert to string and compare. |
| right | const [String](../string/)\& | [String](../string/) to compare. |

### Return Value

false if object string representation equals to string, true otherwise.

## System::operator!=(std::nullptr_t, const String\&) function


Checks if string is null.

```cpp
bool System::operator!=(std::nullptr_t, const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | std::nullptr_t | [String](../string/) to check. |

### Return Value

false if string is null, true otherwise.

## System::operator!=(std::nullptr_t, TimeSpan) function




```cpp
constexpr bool System::operator!=(std::nullptr_t, TimeSpan)
```

## System::operator!=(const SharedPtr\<Uri\>\&, const SharedPtr\<Uri\>\&) function


Determines if the URIs represented by the current and specified objects are not equal.

```cpp
bool System::operator!=(const SharedPtr<Uri> &uri1, const SharedPtr<Uri> &uri2)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| uri1 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | The first [Uri](../uri/) object to compare |
| uri2 | const [SharedPtr](../sharedptr/)\<[Uri](../uri/)\>\& | The second [Uri](../uri/) object to compare |

### Return Value

True if URIs not equal, otherwise - false

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [ArraySegment](../arraysegment/)
* Class [DateTime](../datetime/)
* Class [DateTimeOffset](../datetimeoffset/)
* Class [Nullable](../nullable/)
* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Class [String](../string/)
* Class [TimeSpan](../timespan/)
* Class [Uri](../uri/)
* Struct [IsNullable](../isnullable/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)