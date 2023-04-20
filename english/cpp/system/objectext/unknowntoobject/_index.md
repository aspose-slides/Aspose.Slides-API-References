---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API Reference
description: Converts unknown type to Object, handling both smart pointer type and value type situations.
type: docs
weight: 118
url: /cpp/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) method


Converts unknown type to [Object](../../object/), handling both smart pointer type and value type situations.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to convert to [Object](../../object/). |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | T | [Object](../../object/) to convert. |

### Return Value

Smart pointer to [Object](../../object/) being either converted pointer or boxed value.

## ObjectExt::UnknownToObject(const T\&) method


Converts unknown type to [Object](../../object/), handling both smart pointer type and value type situations.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to convert to [Object](../../object/). |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to convert. |

### Return Value

Smart pointer to [Object](../../object/) being either converted pointer or boxed value.

## See Also

* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Struct [IsSmartPtr](../../issmartptr/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)