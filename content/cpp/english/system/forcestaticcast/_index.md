---
title: ForceStaticCast()
second_title: Aspose.Slides for C++ API Reference
description: Performs real static cast on SmartPtr objects.
type: docs
weight: 2510
url: /system/forcestaticcast/
---
## System::ForceStaticCast(SmartPtr\<TFrom\> const\&) function


Performs real static cast on [SmartPtr](../smartptr/) objects.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ForceStaticCast(SmartPtr<TFrom> const &obj)
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

Cast result if cast is allowed, otherwise the behavior is undefined.

## See Also

* Class [SmartPtr](../smartptr/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)