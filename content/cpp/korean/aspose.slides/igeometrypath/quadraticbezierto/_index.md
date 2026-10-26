---
title: QuadraticBezierTo()
second_title: Aspose.Slides for C++ API 참조
description: 경로 끝에 2차 베지어 곡선을 추가합니다
type: docs
weight: 105
url: /ko/aspose.slides/igeometrypath/quadraticbezierto/
---
## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF) 메서드

경로 끝에 2차 베지어 곡선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝 점 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float) 메서드

경로 끝에 2차 베지어 곡선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | **float** | 방향 점의 X 좌표 |
| y1 | **float** | 방향 점의 Y 좌표 |
| x2 | **float** | 끝 점의 X 좌표 |
| y2 | **float** | 끝 점의 Y 좌표 |

## IGeometryPath::QuadraticBezierTo(System::Drawing::PointF, System::Drawing::PointF, uint32_t) 메서드

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(System::Drawing::PointF point1, System::Drawing::PointF point2, uint32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| point1 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 방향 점 |
| point2 | [System::Drawing::PointF](../../../system.drawing/pointf/) | 끝 점 |
| index | **uint32_t** | PathData에서 세그먼트의 인덱스 |

## IGeometryPath::QuadraticBezierTo(float, float, float, float, uint32_t) 메서드

경로의 지정된 위치에 2차 베지어 곡선을 추가합니다

```cpp
virtual void Aspose::Slides::IGeometryPath::QuadraticBezierTo(float x1, float y1, float x2, float y2, uint32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| x1 | **float** | 방향 점의 X 좌표 |
| y1 | **float** | 방향 점의 Y 좌표 |
| x2 | **float** | 끝 점의 X 좌표 |
| y2 | **float** | 끝 점의 Y 좌표 |
| index | **uint32_t** | PathData에서 세그먼트의 인덱스 |

## 참고

* 클래스 [PointF](../../../system.drawing/pointf/)
* 클래스 [IGeometryPath](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)