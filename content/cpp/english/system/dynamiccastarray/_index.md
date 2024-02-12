---
title: DynamicCastArray()
second_title: Aspose.Slides for C++ API Reference
description: Performs casting of elements of the specified array to different type.
type: docs
weight: 2601
url: /system/dynamiccastarray/
---
## System::DynamicCastArray(const SharedPtr\<Array\<From\>\>\&) function


Performs casting of elements of the specified array to different type.

```cpp
template<class To,class From> SharedPtr<Array<To>> System::DynamicCastArray(const SharedPtr<Array<From>> &from)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | The type to cast the elements of the specified array to |
| From | The type of elements of the elements of the arry elements of which to cast |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| from | const [SharedPtr](../sharedptr/)\<[Array](../array/)\<From\>\>\& | Shared pointer to the array containing the elements to cast |

### Return Value

A pointer to a new array containing elements of type **To** equivalent to the elements of **from**

Deprecated
:   Added for backward compatibility. Use ExplicitCast instead.

## See Also

* Typedef [SharedPtr](../sharedptr/)
* Class [Array](../array/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)