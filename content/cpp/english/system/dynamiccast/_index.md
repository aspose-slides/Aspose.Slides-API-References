---
title: DynamicCast()
second_title: Aspose.Slides for C++ API Reference
description: Performs dynamic cast on Exception objects.
type: docs
weight: 2471
url: /system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) function


Performs dynamic cast on Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | Source Exception type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source pointer. |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\> const\&) function


Performs dynamic cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | Source pointer. |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\>) function


Unboxes boxed enum via cast.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target enum type. |
| TFrom | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Pointer to the object to unbox data from. |

### Return Value

Unboxed enum value.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(std::nullptr_t) function


Performs dynamic cast of null objects.

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |

### Return Value

nullptr.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(TFrom\&) function


Performs dynamic cast on non-pointer objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | TFrom\& | Source object. |

### Return Value

Cast result.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(SmartPtr\<TFrom\>) function


Performs dynamic cast on Objects to Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target Exception type. |
| TFrom | [Object](../object/) type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | Source pointer. |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## System::DynamicCast(TFrom) function


Performs dynamic cast from IntPtr to pointer.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | TFrom | Source IntPtr value. |

### Return Value

Cast result.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## See Also

* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)