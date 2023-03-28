---
title: Is()
second_title: Aspose.Slides for C++ API Reference
description: Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.
type: docs
weight: 105
url: /cpp/system/objectext/is/
---
## ObjectExt::Is(const U\&) method


Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const U\&) method


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Struct [IsBoxable](../../isboxable/)
* Struct [IsSmartPtr](../../issmartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [Object](../../object/)\&) method


Implements 'is' operator translation. Specialization for value types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [Object](../../object/)\&) method


Implements 'is' operator translation. Specialization for unconvertible types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

Always returns false as types are unconvertible.

## See Also

* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [SmartPtr](../../smartptr/)\<U\>\&) method


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\&) method


Implements 'is' operator translation. Specialization for exception wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Struct [IsExceptionWrapper](../../isexceptionwrapper/)
* Class [ExceptionWrapper](../../exceptionwrapper/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\&) method


Implements 'is' operator translation. Specialization for nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Struct [IsNullable](../../isnullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\&) method


Implements 'is' operator translation. Specialization for boxable types with == operator defined.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Struct [IsBoxable](../../isboxable/)
* Struct [IsNullable](../../isnullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\&) method


Implements 'is' operator translation. Specialization for boxable types without defined ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Struct [IsBoxable](../../isboxable/)
* Struct [IsNullable](../../isnullable/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [SmartPtr](../../smartptr/)\<U\>\&) method


Implements 'is' operator translation. Specialization for enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [WeakPtr](../../weakptr/)\<U\>\&) method


Implements 'is' operator translation. Specialization for enum types vs weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [WeakPtr](../../weakptr/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const [Nullable](../../nullable/)\<U\>\&) method


Implements 'is' operator translation. Specialization for [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) type. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [Nullable](../../nullable/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(const char16_t *) method


Implements 'is' operator translation. Specialization for string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::Is(**int32_t**) method


Implements 'is' operator translation. Specialization for integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Target type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | integer literal. |

### Return Value

True if 'is' returns true, false otherwise.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
