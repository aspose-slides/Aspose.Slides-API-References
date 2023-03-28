---
title: Cast()
second_title: Aspose.Slides for C++ API Reference
description: Casts the source type to the result type. Used when the source and the result types are the same.
type: docs
weight: 14
url: /cpp/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source and the result types are the same.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source type can be statically cast to the result type.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the types aren't the same and the source type cannot be statically cast to the result type.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source type is being boxed to the [Nullable](../../system/nullable/) class instance.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source type is being unboxed from the [Nullable](../../system/nullable/) class instance.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source type is being boxed to the [Object](../../system/object/) class instance.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the source type is being unboxed from the [Object](../../system/object/) class instance.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
## System::Collections::Generic::Details::CastRules::Cast(Source) function


Casts the source type to the result type. Used when the casting is invalid or the conversion is explicit.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

The cast result.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)
