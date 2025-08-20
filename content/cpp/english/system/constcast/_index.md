---
title: ConstCast()
second_title: Aspose.Slides for C++ API Reference
description: End of deprecated casts.
type: docs
weight: 2302
url: /system/constcast/
---
## System::ConstCast(const SmartPtr\<TFrom\>\&) function


End of deprecated casts.

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::ConstCast(const SmartPtr<TFrom> &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| TTo | Target pointee type. |
| TFrom | Source pointee type. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../smartptr/)\<TFrom\>\& | Source pointer. |

### Return Value

Cast result if cast is allowed or nullptr otherwise.
## Remarks


Performs const cast on [SmartPtr](../smartptr/) objects. 
## See Also

* Class [SmartPtr](../smartptr/)
* Struct [CastResult](../castresult/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)