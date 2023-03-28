---
title: StaticCast()
second_title: Aspose.Slides for C++ API Reference
description: Performs static cast on SmartPtr objects.
type: docs
weight: 2185
url: /cpp/system/staticcast/
---
## System::StaticCast([SmartPtr](../smartptr/)\<TFrom\> const\&) function


Performs static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
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
## System::StaticCast([WeakPtr](../weakptr/)\<TFrom\> const\&) function


Performs static cast on [WeakPtr](../weakptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
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

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## See Also

* Struct [CastResult](../castresult/)
* Class [WeakPtr](../weakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::StaticCast(std::nullptr_t) function


Performs static cast of null objects.

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
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
## System::StaticCast(TFrom) function


Specialization for arithmetic types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::StaticCast(TTo) function


Process cast from [String](../string/) to [String](../string/).

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## See Also

* Class [String](../string/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::StaticCast(const TFrom *) function


Specialization for arithmetic types.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::StaticCast(const TFrom\&) function


Performs static cast on non-pointer objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target type. |
| TFrom | Source type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const TFrom\& | Source object. |

### Return Value

Cast result if cast is allowed.

Deprecated
:   Left for backwards compatibility. Use ExplicitCast instead.

## See Also

* Class [String](../string/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Struct [IsSmartPtr](../issmartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
## System::StaticCast(const TFrom\&) function


Performs static cast on Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
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
## System::StaticCast([SmartPtr](../smartptr/)\<TFrom\>) function


Performs static cast on Objects to Exception objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
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
