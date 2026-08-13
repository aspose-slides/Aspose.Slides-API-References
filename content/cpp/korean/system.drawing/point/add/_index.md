---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 Size 객체의 너비와 높이 값을 지정된 Point 객체의 X 및 Y 좌표 값에 각각 추가합니다.
type: docs
weight: 183
url: /ko/system.drawing/point/add/
---
## Point::Add(const Point\&, const Size\&) 메서드

[Size](../../size/) 객체의 너비와 높이 값을 [Point](../) 객체의 X 및 Y 좌표값에 각각 추가합니다.

```cpp
static Point System::Drawing::Point::Add(const Point &point, const Size &size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [Point](../)\& | point을 변환 |
| size | const [Size](../../size/)\& | [Size](../../size/) 객체로, 좌표 값에 **point**에 추가할 값을 지정합니다 |

### 반환값

새로운 [Point](../) 객체로, X 좌표값은 **point**의 X 좌표값과 **size**의 너비 값을 더한 것과 같으며, Y 좌표값은 **point**의 Y 좌표값과 **size**의 높이 값을 더한 것과 같습니다.

## 참고

* 클래스 [Point](../)
* 클래스 [Size](../../size/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)