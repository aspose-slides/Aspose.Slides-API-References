---
title: AddCurve()
second_title: Aspose.Slides for C++ API 참조
description: 현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다.
type: docs
weight: 274
url: /ko/system.drawing.drawing2d/graphicspath/addcurve/
---
## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, float) 메서드

현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, float tension=0.5)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 곡선을 정의하는 점 |
| tension | **float** | 제어점 사이에서 곡선이 구부러지는 정도를 지정합니다. |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, float) 메서드

현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, float tension=0.5)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 곡선을 정의하는 점 |
| tension | **float** | 제어점 사이에서 곡선이 구부러지는 정도를 지정합니다. |

## GraphicsPath::AddCurve(const ArrayPtr\<PointF\>\&, int, int, float) 메서드

현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<PointF> &points, int offset, int number_of_segments, float tension)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 곡선을 정의하는 점 |
| offset | int | **points** 내에서 곡선의 시작점으로 사용되는 점의 인덱스 |
| number_of_segments | int | 곡선을 그리는 데 사용되는 세그먼트 수 |
| tension | **float** | 제어점 사이에서 곡선이 구부러지는 정도를 지정합니다. |

## GraphicsPath::AddCurve(const ArrayPtr\<Point\>\&, int, int, float) 메서드

현재 객체가 나타내는 경로에 지정된 곡선을 추가합니다.

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddCurve(const ArrayPtr<Point> &points, int offset, int number_of_segments, float tension)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| points | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 곡선을 정의하는 점 |
| offset | int | **points** 내에서 곡선의 시작점으로 사용되는 점의 인덱스 |
| number_of_segments | int | 곡선을 그리는 데 사용되는 세그먼트 수 |
| tension | **float** | 제어점 사이에서 곡선이 구부러지는 정도를 지정합니다. |

## 참조

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [GraphicsPath](../)
* 클래스 [Point](../../../system.drawing/point/)
* 네임스페이스 [System::Drawing::Drawing2D](../../)
* 라이브러리 [Aspose.Slides](../../../)