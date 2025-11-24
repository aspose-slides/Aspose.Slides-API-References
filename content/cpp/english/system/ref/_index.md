---
title: Ref()
second_title: Aspose.Slides for C++ API Reference
description: Creates reference to DynamicWeakPtr object. Used by translator when passing function arguments by reference.
type: docs
weight: 2380
url: /system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) function


Creates reference to [DynamicWeakPtr](../dynamicweakptr/) object. Used by translator when passing function arguments by reference.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Pointee type. |
| trunkMode | Mode of smart pointer itself. |
| weakLeafs | Indexes of template arguments for which SetTemplateWeakPtr method must be called. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Smart pointer to create reference to. |

### Return Value

Smart pointer reference.

## System::Ref(T\&) function


Helper function to acquire references to objects. Used to guarantee that [System::DynamicWeakPtr](../dynamicweakptr/) updates referenced object after assignments.

```cpp
template<typename T> T & System::Ref(T &value)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to create reference to. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | T\& | Value to create reference to. |

### Return Value

Reference to the value passed to this function.

## See Also

* Class [DynamicWeakPtr](../dynamicweakptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)