---
title: StaticCast_noexcept()
second_title: Aspose.Slides for C++ API Reference
description: Performs static cast on SmartPtr objects.
type: docs
weight: 2185
url: /system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) function


Performs static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
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

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) function


Performs static cast on [WeakPtr](../weakptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | Source pointer. |

### Return Value

Cast result if cast is allowed or nullptr otherwise.

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(const TFrom\&) function


Performs static cast on Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
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

Deprecated
:   Left for backwards compatibility. Use AsCast instead.

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) function


Performs static cast on Objects to Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
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
* Class [WeakPtr](../weakptr/)
* Class [Object](../object/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)