---
title: Cast()
second_title: Aspose.Slides for C++ API Reference
description: Performs cast on SmartPtr objects.
type: docs
weight: 2133
url: /cpp/system/cast/
---
## System::Cast([SmartPtr](../smartptr/)\<TFrom\> const\&) function


Performs cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast(SmartPtr<TFrom> const &obj)
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

## See Also

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Class [SmartPtr](../smartptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)
