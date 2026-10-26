---
title: RotateAt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 객체가 나타내는 행렬을 지정된 각도만큼 시계 방향으로 지정된 점을 중심으로 회전시킵니다.
type: docs
weight: 144
url: /ko/system.drawing.drawing2d/matrix/rotateat/
---
## Matrix::RotateAt(float, const PointF\&) 메서드

현재 객체가 나타내는 행렬을 지정된 각도만큼 시계 방향으로 지정된 점을 중심으로 회전시킵니다.

```cpp
void System::Drawing::Drawing2D::Matrix::RotateAt(float angle, const PointF &point)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | **float** | 행렬을 회전시킬 각도 |
| point | const [PointF](../../../system.drawing/pointf/)\& | 회전 중심점을 지정합니다 |

## Matrix::RotateAt(float, const PointF\&, MatrixOrder) 메서드

현재 객체가 나타내는 행렬을 지정된 각도만큼 시계 방향으로 지정된 점을 중심으로 회전시킵니다.

```cpp
void System::Drawing::Drawing2D::Matrix::RotateAt(float angle, const PointF &point, MatrixOrder order)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| angle | **float** | 행렬을 회전시킬 각도 |
| point | const [PointF](../../../system.drawing/pointf/)\& | 회전 중심점을 지정합니다 |
| order | [MatrixOrder](../../matrixorder/) | 회전이 적용되는 순서 |

## 관련 항목

* 열거형 [MatrixOrder](../../matrixorder/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [Matrix](../)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)