---
title: Unbox()
second_title: Aspose.Slides for C++ API Reference
description: Unboxes value types after converting to Object. Implementation for enum types.
type: docs
weight: 53
url: /cpp/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for enum types.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to unbox. |

### Return Value

[Enum](../../enum/) value.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for non-enum & non-nullable types.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to unbox. |

### Return Value

Unboxed value.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes value types after converting to [Object](../../object/). Implementation for non-enum & non-nullable types.

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to unbox. |

### Return Value

Unboxed value.

## ObjectExt::Unbox(E) method


Unboxes enum types to integer.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Destination integer type. |
| E | Source enum type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to unbox. |

### Return Value

Integer representation of enum.

## ObjectExt::Unbox(E) method


Converts enum types.

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Destination enum type. |
| E | Source enum type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| e | E | Value to unbox. |

### Return Value

Converted enum value.

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method


Unboxes string values.

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to unbox |

### Return Value

[String](../../string/) representation of boxed string, can be null if boxed string was null.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)