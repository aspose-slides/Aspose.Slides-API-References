---
title: GetHashCode()
second_title: Aspose.Slides for C++ API Reference
description: "Gets hash code on arbitrary type. Calls Object::GetHashCode() to do so."
type: docs
weight: 1
url: /cpp/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) method


Gets hash code on arbitrary type. Calls [Object::GetHashCode()](../../../system/object/gethashcode/) to do so.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T | Type to get hash code for. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) to get information from. |

### Return Value

Hash code value as calcualted by target implementation.

## See Also

* Class [SmartPtr](../../../system/smartptr/)
* Class [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.Slides](../../../)