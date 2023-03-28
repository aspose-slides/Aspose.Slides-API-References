---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 27
url: /cpp/system/objectext/equals/
---
## ObjectExt::Equals(const T\&, const T2\&) method




```cpp
template<typename T,typename T2> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```

## See Also

* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for smart pointer types.

```cpp
template<typename T,typename T2> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Return Value

True if objects are considered equal, false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(T, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for structure types.

```cpp
template<typename T,typename T2> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(T obj, const T2 &another)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | First object. |
| another | const T2\& | Second object. |

### Return Value

True if objects are considered equal, false otherwise.

## See Also

* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(const T\&, const T2\&) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for scalar types.

```cpp
template<typename T,typename T2> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value, bool>::type System::ObjectExt::Equals(const T &obj, const T2 &another)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | First object type. |
| T2 | Second object type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | First object. |
| another | const T2\& | Second object. |

### Return Value

True if objects are considered equal, false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(const char_t(&), [String](../../string/)) method


Substitution for C# [Object.Equals](../../object/equals/) calls working for any type in C++. Overload for string literal with string comparison.

```cpp
template<size_t> static bool System::ObjectExt::Equals(const char_t(&obj)[N], String another)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| N | [String](../../string/) literal size. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t(&) | [String](../../string/) literal. |
| another | [String](../../string/) | [String](../../string/). |

### Return Value

True if strings match, false otherwise.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(const **float**\&, const **float**\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::ObjectExt::Equals(const float &obj, const float &another)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **float**\& | LHS floating point value. |
| another | const **float**\& | RHS floating point value. |

### Return Value

True if **obj** and **another** are both NaN or equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Equals(const **double**\&, const **double**\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::ObjectExt::Equals(const double &obj, const double &another)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const **double**\& | LHS floating point value. |
| another | const **double**\& | RHS floating point value. |

### Return Value

True if **obj** and **another** are both NaN or equal, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
