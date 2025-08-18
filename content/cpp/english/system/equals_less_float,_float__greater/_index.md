---
title: Equals< float, float >()
second_title: Aspose.Slides for C++ API Reference
description: "Specialization for single-precision floating point values. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for System.Object.Equals, requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard."
type: docs
weight: 2445
url: /system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) function


Specialization for single-precision floating point values. Although two floating point NaNs are defined by IEC 60559:1989 to always compare as unequal, the contract for [System.Object.Equals](../object/equals/), requires that overrides must satisfy the requirements for an equivalence operator. Therefore, System.Double.Equals and System.Single.Equals return True when comparing two NaNs, while the equality operator returns False in that case, as required by the standard.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| a | const **float**\& | The first comparand |
| b | const **float**\& | The second comparand |

### Return Value

True if both values are NaN or are equal, otherwise - false

## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)