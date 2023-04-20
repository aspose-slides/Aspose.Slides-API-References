---
title: IsNull()
second_title: Aspose.Slides for C++ API Reference
description: Checks that the represented value is nullptr.
type: docs
weight: 14
url: /cpp/system.collections.generic.details.castrules/isnull/
---
## System::Collections::Generic::Details::CastRules::IsNull(T) function


Checks that the represented value is nullptr.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(T)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The value type. |

### Return Value

Always returns false.

## System::Collections::Generic::Details::CastRules::IsNull(SharedPtr\<T\>) function


Checks that the represented value is nullptr.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(SharedPtr<T> value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [SharedPtr](../../system/sharedptr/)\<T\> | The value that must be checked. |

### Return Value

True if the value is nullptr, otherwise false.

## System::Collections::Generic::Details::CastRules::IsNull(Nullable\<T\>) function


Checks that the represented value is nullptr.

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(Nullable<T> value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | The value type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Nullable](../../system/nullable/)\<T\> | The value that must be checked. |

### Return Value

True if the value is nullptr, otherwise false.

## See Also

* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Nullable](../../system/nullable/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)