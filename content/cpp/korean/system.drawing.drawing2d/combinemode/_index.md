---
title: CombineMode
second_title: Aspose.Slides for C++ API 레퍼런스
description: 클리핑 영역이 결합되는 방식을 지정합니다.
type: docs
weight: 170
url: /ko/system.drawing.drawing2d/combinemode/
---
## CombineMode 열거형

클리핑 영역이 결합되는 방식을 지정합니다.

```cpp
enum class CombineMode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| Replace | 0 | 하나의 클리핑 영역이 다른 영역으로 교체됩니다. |
| Intersect | 1 | 두 클리핑 영역은 교차점을 취하여 결합됩니다. |
| Union | 2 | 두 클리핑 영역은 두 영역의 합집합을 취하여 결합됩니다. |
| Xor | 3 | 두 클리핑 영역은 한쪽 영역에만 포함된 영역을 취하여 결합되며, 두 영역 모두에 포함된 영역은 제외됩니다. |
| Exclude | 4 | 두 클리핑 영역은 첫 번째 영역 중 두 번째와 교차하지 않는 영역을 취하여 결합됩니다. |
| Complement | 5 | 두 클리핑 영역은 두 번째 영역 중 첫 번째와 교차하지 않는 영역을 취하여 결합됩니다. |

## See Also

* Namespace [System::Drawing::Drawing2D](../)
* Library [Aspose.Slides](../../)