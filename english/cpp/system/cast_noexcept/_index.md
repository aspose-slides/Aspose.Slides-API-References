---
title: Cast_noexcept()
second_title: Aspose.Slides for C++ API Reference
description: Performs cast on SmartPtr objects.
type: docs
weight: 2120
url: /cpp/system/cast_noexcept/
---
## System::Cast_noexcept(SmartPtr\<TFrom\> const\&) function


Performs cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::Cast_noexcept(SmartPtr<TFrom> const &obj)
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

Cast result if cast is allowed or nullptr otherwise.

## See Also

* Class [SmartPtr](../smartptr/)
* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)