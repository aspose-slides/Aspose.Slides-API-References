---
title: ToString()
second_title: Aspose.Slides for C++ API Reference
description: Substitution for C# ToString method to work on any C++ type.
type: docs
weight: 40
url: /cpp/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) method


Substitution for C# ToString method to work on any C++ type.

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) literal to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(const [Nullable](../../nullable/)\<T\>\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Nullable](../../nullable/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) object to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Smart pointer type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Smart pointer type or [ExceptionWrapper](../../exceptionwrapper/). |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Smart pointer or [ExceptionWrapper](../../exceptionwrapper/) to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Scalar type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Scalar value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(T\&&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Scalar type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\&& | Scalar value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Structure type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\& | Structure value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsNullable](../../isnullable/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(const T\&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Structure type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | Structure value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsNullable](../../isnullable/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ToString(T\&&) method


Substitution for C# ToString method to work on any C++ type.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Scalar type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T\&& | Scalar value to convert to string. |

### Return Value

[String](../../string/) representation of **obj**.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Struct [IsNullable](../../isnullable/)
* Class [String](../../string/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
