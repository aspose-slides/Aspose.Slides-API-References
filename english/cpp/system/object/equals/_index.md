---
title: Equals()
second_title: Aspose.Slides for C++ API Reference
description: Compares objects using C# Object.Equals semantics.
type: docs
weight: 157
url: /cpp/system/object/equals/
---
## Object::Equals([ptr](../ptr/)) method


Compares objects using C# [Object.Equals](./) semantics.

```cpp
virtual bool System::Object::Equals(ptr obj)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [ptr](../ptr/) | [Object](../) to compare current one to. |

### Return Value

True if objects are considered equal and false otherwise.

## See Also

* Typedef [ptr](../ptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Compares reference type objects in C# style.

```cpp
template<typename T1,typename T2> static std::enable_if<IsSmartPtr<T1>::value &&IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Type of first object to compare. |
| T2 | Type of second object to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T1 const\& | First object to compare. |
| objB | T2 const\& | Second object to compare. |

### Return Value

True if objects match either by reference or semantically (by [Object.Equals](./)-alike comparison), false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::Equals(T1 const\&, T2 const\&) method


Compares value type objects in C# style.

```cpp
template<typename T1,typename T2> static std::enable_if<!IsSmartPtr<T1>::value &&!IsSmartPtr<T2>::value, bool>::type System::Object::Equals(T1 const &objA, T2 const &objB)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Type of first object to compare. |
| T2 | Type of second object to compare. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | T1 const\& | First object to compare. |
| objB | T2 const\& | Second object to compare. |

### Return Value

True if objects are considered equal by equality operator available, false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::Equals(**float** const\&, **float** const\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::Object::Equals(float const &objA, float const &objB)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | **float** const\& | LHS floating point value. |
| objB | **float** const\& | RHS floating point value. |

### Return Value

True if **objA** and **objB** are both NaN or equal, false otherwise.

## See Also

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## Object::Equals(**double** const\&, **double** const\&) method


Emulates C#-style floating point comparison where two NaNs are considered equal even though according to IEC 60559:1989 NaN is not equal to any value, including NaN.

```cpp
bool System::Object::Equals(double const &objA, double const &objB)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| objA | **double** const\& | LHS floating point value. |
| objB | **double** const\& | RHS floating point value. |

### Return Value

True if **objA** and **objB** are both NaN or equal, false otherwise.

## See Also

* Class [Object](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
