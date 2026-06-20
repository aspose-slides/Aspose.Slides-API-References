---
title: RoundImpl()
second_title: Aspose.Slides for C++ API Reference
description: Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.
type: docs
weight: 287
url: /system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) method


Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | The value to round |
| digits | int | The number of fractional digits in the rounded value |
| mode | [MidpointRounding](../../midpointrounding/) | Specifies how to perform the rounding if **value** is equally close to two nearest numbers. |

### Return Value

The number with the specified number of digits nearest to **value**

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)