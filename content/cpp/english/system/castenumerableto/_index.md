---
title: CastEnumerableTo()
second_title: Aspose.Slides for C++ API Reference
description: Performs the explicit casting of elements of the specified enumerable object to different type.
type: docs
weight: 2887
url: /system/castenumerableto/
---
## System::CastEnumerableTo(const From\&) function


Performs the explicit casting of elements of the specified enumerable object to different type.

```cpp
template<class To,class From> std::enable_if<!System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | The type to statically cast the elements of the enumerable object to |
| From | The type of enumerable object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | const From\& | Enumerable object containing the elements to cast |

### Return Value

A pointer to a new collection containing elements of type **To** equivalent to the elements of **enumerable**

## System::CastEnumerableTo(const From\&) function


Performs the explicit casting of elements of the specified enumerable object to different type.

```cpp
template<class To,class From> std::enable_if<System::detail::has_method_get_Count<From>::value, Collections::Generic::ListPtr<To>>::type System::CastEnumerableTo(const From &enumerable)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | The type to statically cast the elements of the enumerable object to |
| From | The type of enumerable object |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| enumerable | const From\& | is inheritor of Enumerable object with defined get_Count method and containing the elements to cast |

### Return Value

A pointer to a new collection containing elements of type **To** equivalent to the elements of **enumerable**

## See Also

* Class [ListPtr](../../system.collections.generic/listptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)