---
title: Contains()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 점이 현재 객체가 나타내는 사각형 내부에 있는지 확인합니다.
type: docs
weight: 248
url: /ko/system.drawing/rectanglef/contains/
---
## RectangleF::Contains(float, float) 메서드

Determines if the specified point is located within the rectangle represented by the current object.

```cpp
bool System::Drawing::RectangleF::Contains(float x, float y)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x | **float** | 확인할 점의 X 좌표 |
| y | **float** | 확인할 점의 Y 좌표 |

### 반환 값

지정된 점이 현재 객체가 나타내는 사각형 내부에 있으면 true, 그렇지 않으면 false

## RectangleF::Contains(const PointF\&) 메서드

Determines if the specified point is located within the rectangle represented by the current object.

```cpp
bool System::Drawing::RectangleF::Contains(const PointF &point)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point | const [PointF](../../pointf/)\& | 확인할 점 |

### 반환 값

지정된 점이 현재 객체가 나타내는 사각형 내부에 있으면 true, 그렇지 않으면 false

## RectangleF::Contains(const RectangleF\&) 메서드

Determines if the specified rectangle is located within the rectangle represented by the current object.

```cpp
bool System::Drawing::RectangleF::Contains(const RectangleF &rect)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | const [RectangleF](../)\& | 확인할 사각형 |

### 반환 값

지정된 사각형이 현재 객체가 나타내는 사각형 내부에 있으면 true, 그렇지 않으면 false

## 참고

* 클래스 [RectangleF](../)
* 클래스 [PointF](../../pointf/)
* 네임스페이스 [System::Drawing](../../)
* 라이브러리 [Aspose.Slides](../../../)