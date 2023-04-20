---
title: DynamicCast_noexcept()
second_title: Aspose.Slides for C++ API Reference
description: Old obsolete casts. Will be removed in future versions.
type: docs
weight: 1860
url: /cpp/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) function


Old obsolete casts. Will be removed in future versions.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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

Cast result if cast is allowed or nullptr otherwise.
## Remarks


Performs dynamic cast on Exception objects. Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) function


Performs dynamic cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) function


Performs dynamic cast on Objects to Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## See Also

* Class [SmartPtr](../smartptr/)
* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)