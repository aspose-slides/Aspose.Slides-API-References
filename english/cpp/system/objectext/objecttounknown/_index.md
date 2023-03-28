---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API Reference
description: Converts Object to unknown type, handling both smart pointer type and bpxed value situations.
type: docs
weight: 144
url: /cpp/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown([SmartPtr](../../smartptr/)\<[Object](../../object/)\>) method


Converts [Object](../../object/) to unknown type, handling both smart pointer type and bpxed value situations.

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to convert [Object](../../object/) to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) to convert. |

### Return Value

Either unboxed value or converted pointer.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
## ObjectExt::ObjectToUnknown([SmartPtr](../../smartptr/)\<[Object](../../object/)\>) method


Converts [Object](../../object/) to unknown type, handling both smart pointer type and boxed value situations.

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to convert [Object](../../object/) to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) to convert. |

### Return Value

Either unboxed value or converted pointer.

## See Also

* Struct [IsSmartPtr](../../issmartptr/)
* Class [SmartPtr](../../smartptr/)
* Class [Object](../../object/)
* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)
