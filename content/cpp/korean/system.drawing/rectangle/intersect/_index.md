---
title: Intersect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 사각형을 지정된 객체가 나타내는 사각형과의 교차 결과로 얻어지는 사각형으로 교체합니다.
type: docs
weight: 274
url: /ko/system.drawing/rectangle/intersect/
---
## Rectangle::Intersect(const Rectangle\&) 메서드

현재 객체가 나타내는 사각형을 지정된 객체가 나타내는 사각형과의 교차 결과로 얻어지는 사각형으로 교체합니다.

```cpp
void System::Drawing::Rectangle::Intersect(const Rectangle &rect)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [Rectangle](../)\& | 현재 객체가 나타내는 사각형과 교차할 사각형을 나타내는 [Rectangle](../) 객체 |

## Rectangle::Intersect(const Rectangle\&, const Rectangle\&) 메서드

지정된 두 사각형의 교차 결과로 얻어지는 사각형을 반환합니다.

```cpp
static Rectangle System::Drawing::Rectangle::Intersect(const Rectangle &a, const Rectangle &b)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| a | const [Rectangle](../)\& | 교차할 첫 번째 사각형 |
| b | const [Rectangle](../)\& | 교차할 두 번째 사각형 |

### 반환값

**a**와 **b**의 교차 결과

## 참고

* 클래스 [Rectangle](../)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)