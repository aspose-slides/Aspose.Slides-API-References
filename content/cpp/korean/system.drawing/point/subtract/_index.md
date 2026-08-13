---
title: Subtract()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 Size 객체의 너비와 높이 값을 지정된 Point 객체의 X 및 Y 좌표값에서 각각 빼습니다.
type: docs
weight: 196
url: /ko/system.drawing/point/subtract/
---
## Point::Subtract(const Point\&, const Size\&) 메서드


지정된 [Size](../../size/) 객체의 너비와 높이 값을 지정된 [Point](../) 객체의 X 및 Y 좌표값에서 각각 빼습니다.

```cpp
static Point System::Drawing::Point::Subtract(const Point &point, const Size &size)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| point | const [Point](../)\& | 변환할 점 |
| size | const [Size](../../size/)\& | [Size](../../size/) 객체는 **point**의 좌표값에서 빼야 할 값을 지정합니다. |

### 반환 값

새로운 [Point](../) 객체로, X 좌표값은 **point**의 X 좌표값에서 **size**의 너비 값을 빼는 결과와 같으며, Y 좌표값은 **point**의 Y 좌표값에서 **size**의 높이 값을 빼는 결과와 같습니다.

## 또 보기

* 클래스 [Point](../)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)