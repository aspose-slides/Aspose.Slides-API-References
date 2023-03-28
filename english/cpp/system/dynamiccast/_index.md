---
title: DynamicCast()
second_title: Aspose.Slides for C++ API Reference
description: Performs dynamic cast on Exception objects.
type: docs
weight: 2159
url: /cpp/system/dynamiccast/
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

## See Also

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::DynamicCast([SmartPtr](../smartptr/)\<TFrom\> const\&) function


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

## See Also

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::DynamicCast([SmartPtr](../smartptr/)\<TFrom\>) function


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

## See Also

* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
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

## See Also

* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
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

## See Also

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::DynamicCast([SmartPtr](../smartptr/)\<TFrom\>) function


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

## See Also

* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
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

* Namespace [System](../)
* Library [Aspose.Slides](../../)
