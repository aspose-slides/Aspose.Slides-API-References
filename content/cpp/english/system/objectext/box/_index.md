---
title: Box()
second_title: Aspose.Slides for C++ API Reference
description: Boxes value types for converting to Object. Implementation for enum types.
type: docs
weight: 40
url: /system/objectext/box/
---
## ObjectExt::Box(const T\&) method


Boxes value types for converting to [Object](../../object/). Implementation for enum types.

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | [Enum](../../enum/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | [Enum](../../enum/) value to box. |

### Return Value

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) method


Boxes value types for converting to [Object](../../object/). Implementation for non-enum types.

```cpp
template<typename T> static std::enable_if<!std::is_enum<T>::value &&!IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Return Value

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const T\&) method


Boxes [Nullable](../../nullable/) types for converting to [Object](../../object/).

```cpp
template<typename T> static std::enable_if<IsNullable<T>::value, System::SmartPtr<System::Object>>::type System::ObjectExt::Box(const T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const T\& | Value to box. |

### Return Value

Smart pointer to object keeping boxed value.

## ObjectExt::Box(const String\&) method


Boxes string values.

```cpp
SmartPtr<Object> System::ObjectExt::Box(const String &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | Value to box. |

### Return Value

Boxed value or null, if source string is null.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Class [String](../../string/)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)