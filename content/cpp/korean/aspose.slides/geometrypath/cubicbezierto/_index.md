---
title: CubicBezierTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 경로 끝에 cubic Bezier 곡선을 추가합니다
type: docs
weight: 105
url: /ko/aspose.slides/geometrypath/cubicbezierto/
---
## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF) 메서드

경로 끝에 cubic Bezier 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 첫 번째 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 두 번째 방향 점 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float) 메서드

경로 끝에 cubic Bezier 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | **float** | 첫 번째 방향 점의 X 좌표 |
| y1 | **float** | 첫 번째 방향 점의 Y 좌표 |
| x2 | **float** | 두 번째 방향 점의 X 좌표 |
| y2 | **float** | 두 번째 방향 점의 Y 좌표 |
| x3 | **float** | 끝점의 X 좌표 |
| y3 | **float** | 끝점의 Y 좌표 |

## GeometryPath::CubicBezierTo(System::Drawing::PointF, System::Drawing::PointF, System::Drawing::PointF, uint32_t) 메서드

경로 지정 위치에 cubic Bezier 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, System::Drawing::PointF point3, uint32_t index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 첫 번째 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 두 번째 방향 점 |
| point3 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝점 |
| index | **uint32_t** | PathData에서 세그먼트의 인덱스 |

## GeometryPath::CubicBezierTo(float, float, float, float, float, float, uint32_t) 메서드

경로 지정 위치에 cubic Bezier 곡선을 추가합니다

```cpp
void Aspose::Slides::GeometryPath::CubicBezierTo(float x1, float y1, float x2, float y2, float x3, float y3, uint32_t index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | **float** | 첫 번째 방향 점의 X 좌표 |
| y1 | **float** | 첫 번째 방향 점의 Y 좌표 |
| x2 | **float** | 두 번째 방향 점의 X 좌표 |
| y2 | **float** | 두 번째 방향 점의 Y 좌표 |
| x3 | **float** | 끝점의 X 좌표 |
| y3 | **float** | 끝점의 Y 좌표 |
| index | **uint32_t** | PathData에서 세그먼트의 인덱스 |

## 참고

* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [GeometryPath](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)