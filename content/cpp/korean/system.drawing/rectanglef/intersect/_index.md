---
title: Intersect()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 사각형을 지정된 객체가 나타내는 사각형과의 교차 결과로 얻어지는 사각형으로 교체합니다.
type: docs
weight: 274
url: /ko/system.drawing/rectanglef/intersect/
---
## RectangleF::Intersect(const RectangleF\&) 메서드

현재 객체가 나타내는 사각형을 지정된 객체가 나타내는 사각형과의 교차 결과로 얻어지는 사각형으로 교체합니다.

```cpp
void System::Drawing::RectangleF::Intersect(const RectangleF &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 현재 객체가 나타내는 사각형과 교차할 사각형을 나타내는 [RectangleF](../) 객체 |

## RectangleF::Intersect(const RectangleF\&, const RectangleF\&) 메서드

지정된 사각형들의 교차 결과인 사각형을 반환합니다.

```cpp
static RectangleF System::Drawing::RectangleF::Intersect(const RectangleF &a, const RectangleF &b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const [RectangleF](../)\& | 교차할 첫 번째 사각형 |
| b | const [RectangleF](../)\& | 교차할 두 번째 사각형 |

### 반환 값

**a**와 **b**의 교차 결과

## 참고

* 클래스 [RectangleF](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)