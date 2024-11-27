---
title: GetUnderlyingType()
second_title: Aspose.Slides for C++ API Reference
description: Returns the underlying type argument of the specified nullable type.
type: docs
weight: 1
url: /system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) method


Returns the underlying type argument of the specified nullable type.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | A System.Type object that describes a closed generic nullable type. |

### Return Value

The type argument of the nullableType parameter, if the nullableType parameter is a closed generic nullable type; otherwise, null

## See Also

* Class [TypeInfo](../../typeinfo/)
* Class [NullableUtils](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)