---
title: CanCast()
second_title: Aspose.Slides for C++ API Reference
description: Checks the cast possibility.
type: docs
weight: 14
url: /cpp/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

Always returns true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

True when a non nullptr value is returns after casting, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

Always returns true.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

True if the cast operation was successfully done, otherwise false.

## System::Collections::Generic::Details::CastRules::CanCast(Source) function


Checks the cast possibility.

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| Source | The source type. |
| Result | The result type. |

### Return Value

Always returns false.

## See Also

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)