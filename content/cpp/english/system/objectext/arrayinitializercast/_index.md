---
title: ArrayInitializerCast()
second_title: Aspose.Slides for C++ API Reference
description: Converts array fundamental values (which C# does implicitly but C++ apparently does not).
type: docs
weight: 196
url: /system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) method


Converts array fundamental values (which C# does implicitly but C++ apparently does not).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```


### Template parameters

| Parameter | Description |
| --- | --- |
| To | Target type. |
| From | Source types. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | From ... | Values to convert and push to target array. |

### Return Value

[Array](../../array/) containing converted copies of all arguments in the same order.

## See Also

* Class [ObjectExt](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)