---
title: RoundImpl()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 값을 지정된 소수 자릿수로 가장 가까운 값으로 반올림합니다. 매개변수는 지정된 값이 두 가장 가까운 수와 동일하게 가까운 경우 함수의 동작을 지정합니다.
type: docs
weight: 287
url: /ko/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) 메서드

Rounds the specified value to the nearest value with the specified number of fractional digits. A parameter specifies the function's behavior if the specified value is equally close to two nearest numbers.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | 반올림할 값 |
| digits | int | 반올림된 값의 소수 자릿수 |
| mode | [MidpointRounding](../../midpointrounding/) | **value**가 두 가장 가까운 수와 동일하게 가까운 경우 반올림 수행 방법을 지정합니다. |

### Return Value

지정된 자릿수로 **value**에 가장 가까운 숫자

## See Also

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* 네임스페이스 [System](../../)
* Library [Aspose.Slides](../../../)